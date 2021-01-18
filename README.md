# 1. Overview

The Simter Project Builder to build all simter projects.

Modules :

Sn | Name | Remark
:---:|---|---
 1 | simter-build          | Build modules and define global properties and pluginManagement
 2 | simter-dependencies   | Define global dependencyManagement
 3 | simter-parent         | All sub modules parent module, Define global dependencies and plugins
 4 | simter-\[sub-module\] |

Remark : 1, 2, 3 all has maven-enforcer-plugin and flatten-maven-plugin config. \[sub-module\] means simter-core and all other sub modules. They simter-\[sub-module\] must not configure them.

Pom Inherited Structure : (A : B means B is the parent of A)

```
simter-parent : simter-dependencies : simter-build
gftaxi-\[sub-module\] : simter-parent
```

## 2. Requirement

Maven3.6+, Java8+.

## 3. Development build

```shell
$ mvn clean install
```

The default version is `pom.xml/properties/revision` value, can be change through command argument temporary. Below change to version `x.y.z-SHAPSHOT`.

```shell
$ mvn clean install -D revision=x.y.z-SHAPSHOT
```

## 4. Release build

1. Change `pom.xml/properties/revision` value to the release version number.
    ```
    <properties>
      <revision>x.y.z</revision>
    </properties>
    ```
2. Commit a log with format `'Release version x.y.z`.
    ```shell
    $ git add pom.xml
    $ git commit -m "Release version x.y.z"
    ```
3. Release to intranet nexus server.
    ```shell
    $ mvn clean deploy -P lan
    ```
4. Release to bintray.
    ```shell
    $ mvn clean deploy -P bintray
    ```
5. Release to sonatype.
    ```shell
    $ mvn clean deploy -P sonatype
    ```