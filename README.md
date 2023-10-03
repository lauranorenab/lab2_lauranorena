# lab2_lauranorena

[![CI/CD Pipeline](https://github.com/lauranorenab/lab2_lauranorena/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/lauranorenab/lab2_lauranorena/actions/workflows/build.yml)

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=lauranorenab_lab2_lauranorena)](https://sonarcloud.io/summary/new_code?id=lauranorenab_lab2_lauranorena)

[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=lauranorenab_lab2_lauranorena&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=lauranorenab_lab2_lauranorena)

[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=lauranorenab_lab2_lauranorena&metric=coverage)](https://sonarcloud.io/summary/new_code?id=lauranorenab_lab2_lauranorena)

[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=lauranorenab_lab2_lauranorena&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=lauranorenab_lab2_lauranorena)

[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=lauranorenab_lab2_lauranorena&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=lauranorenab_lab2_lauranorena)

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```