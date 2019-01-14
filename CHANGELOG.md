# [simter-build](https://github.com/simter/simter-build) changelog

## 1.0.1 - 2019-01-10

- Add profile `bintray-kotlin` for kotlin module
- Add property `simter-r2dbc-ext=1.1.0`

## 1.0.0 - 2019-01-07 (spring-boot-2.1.1, spring-5.1.3, maven-3.6.0)

- Add submodule simter-exception
- Add submodule simter-jackson-ext
- Add submodule simter-query
- Add submodule simter-r2dbc-ext
- Add submodule simter-reactive-context
- Add submodule simter-reactive-web
- Add submodule simter-reactive-security
- Add submodule simter-reactive-security
- Delete submodule simter-meta-jpa
- Delete submodule simter-meta
- Delete submodule simter-id
- Upgrade dependency management version : 
    - kotlin.version=1.3.11
    - spring.version=5.1.3.RELEASE
    - spring-boot.version=2.1.1.RELEASE
    - mysql.version=8.0.13
    - postgresql.version=42.2.5
    - flapdoodle-embed-mongo.version=2.1.1
    - junit5.platform.version=1.3.2
    - junit5.jupiter.version=5.3.2
    - junit5.vintage.version=5.3.2
    - mockito.version=2.23.4
    - mockito-kotlin.version=1.6.0
    - hibernate.version=5.4.0.Final
    - hibernate-validator.version=6.0.13.Final
    - poi.version=4.0.1
    - maven-surefire-plugin.version=2.22.1
- Add properties : 
    - reactor.version=3.2.3.RELEASE
    - spring-data-r2dbc.version=1.0.0.M1
    - spring-data-jdbc.version=1.1.0.M1
    - r2dbc.version=1.0.0.M6
- Upgrade maven-enforcer-plugin to 3.0.0-M2
- Require minimal maven version 3.6.0

## 0.5.0 - 2018-06-20 (spring-boot-2.0.1, spring-5.0.5, maven-3.5.2)

- Add properties : 
    - kotlin.compiler.incremental=true
    - kotlin.version=1.2.31
    - spring.version=5.0.5.RELEASE
    - spring-boot.version=2.0.1.RELEASE
    - mysql.version=8.0.11
    - postgresql.version=42.2.2
    - flapdoodle-embed-mongo.version=2.0.1
    - mongo-embedded.version=3.5.5
    - junit4.version=4.12
    - junit5.platform.version=1.2.0
    - junit5.jupiter.version=5.2.0
    - junit5.vintage.version=5.2.0
    - mockito.version=2.18.3
    - mockito-kotlin.version=1.5.0
    - hibernate.version=5.2.16.Final
    - hibernate-validator.version=6.0.9.Final
    - poi.version=3.17
    - maven-surefire-plugin.version=2.21.0
- Add submodule simter-mongo-ext
- Add kotlin-maven-plugin management
- Add maven-surefire-plugin management
- Config flatten-maven-plugin generate `flattened-pom.xml` to `target` directory

## 0.4.0 - 2018-01-05 (spring-boot-1.5.9)

- Centralize version

## 0.3.0 - 2017-12-29

- Initial