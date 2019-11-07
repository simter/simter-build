# [simter-build](https://github.com/simter/simter-build) changelog

## 1.3.0-M4 - 2019-11-07

- Upgrade to reactor-Dysprosium-SR1
- Upgrade to spring-data-releasetrain-Moore-SR1
- Upgrade to spring-boot-2.2.1
- Upgrade to spring-5.2.1
- Upgrade to eclipselink-2.7.5
- Upgrade to hibernate-validator-6.1.0.Final
- Upgrade to hibernate-5.4.8.Final
- Upgrade to h2-1.4.200

## 1.3.0-M3 - 2019-10-18

- Upgrade to spring-boot-2.2.0.RELEASE
- Set default postgres-embedded.version=10.10-2
- Set default mysql-embedded.version=8.0.17
- Upgrade to mysql-driver-8.0.18
- Upgrade to hibernate-5.4.6.Final
- Upgrade to mockito-kotlin-2.2.0
- Upgrade to mockito-3.1.0

## 1.3.0-M2 - 2019-10-08

- Upgrade to spring-5.2.0
- Upgrade to spring-data-releasetrain-Moore-RELEASE(2.2.0)
- Upgrade to spring-boot-2.2.0.RC1
- Upgrade to r2dbc-Arabba-RC2(0.8.0.RC2)
- Upgrade to spring-data-r2dbc-1.0.0.RC1
- Upgrade to spring-boot-r2dbc-0.1.0.M2
- Upgrade to springmockk-1.1.3
- Upgrade to postgres-42.2.8
- Upgrade to mysql-8.0.17
- Upgrade to hsql-2.5.0
- Upgrade to derby-10.15.1.3

## 1.3.0-M1 - 2019-09-27

- Upgrade to r2dbc-Arabba-RC1(0.8.0.RC1)
- Upgrade to hibernate-5.4.5
- Upgrade to mockito-3.0.0
- Upgrade to junit-5.5.2
- Upgrade to reactor-Dysprosium-RELEASE(3.3.0)
- Upgrade to spring-data-releasetrain-Lovelace-SR10(2.1.10) and Moore-RC3(2.2.0.RC3)
- Upgrade to spring-boot-2.1.8 and 2.2.0.M6
- Upgrade to spring-5.1.9 and 5.2.0.RC2
- Upgrade to kotlin-1.3.50

## 1.2.1 - 2019-09-27

- Align version with simter-dependency-1.2.1

## 1.2.0 - 2019-07-03 (spring-boot-2.1.6, spring-5.1.8, kotlin-1.3.40, reactor-3.2)

- Upgrade dependency management version : 
    - spring.version=5.1.8.RELEASE
    - spring-boot.version=2.1.6.RELEASE
    - r2dbc.version=Arabba-M8 (spi-0.8.0.M8)
    - reactor.version=Californium-SR9 (core-3.2.10.RELEASE)
    - junit5.version=5.5.0
    - mockk.version=1.9.3
    - springmockk.version=1.1.2
    - hibernate.version=5.4.3.Final
    - hibernate-validator.version=6.0.17.Final
    - eclipselink.version=2.7.4
    - maven-surefire-plugin.version=2.22.2
    - postgres-driver.version=42.2.5
    - mysql-driver.version=8.0.15
    - h2-driver.version=1.4.199
    - hsql-driver.version=2.4.1
    - derby-driver.version=10.14.2.0
- Upgrade milestone dependency management version:
    - spring.milestone.version=5.2.0.M3
    - spring-data-releasetrain.milestone.version=Moore-RC1
    - spring-boot.milestone.version=2.2.0.M4
    - reactor.milestone.version=Dysprosium-M2

## 1.1.0 - 2019-01-14 (spring-boot-2.1.2, spring-5.1.4)

- Upgrade dependency management version : 
    - spring.version=5.1.4.RELEASE
    - spring-boot.version=2.1.2.RELEASE
    - flapdoodle-embed-mongo.version=2.2.0
    - reactor.version=3.2.5.RELEASE
- Delete property `simter-r2dbc-ext`

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