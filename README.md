# caic2024

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=bugs)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=coverage)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=JoseHenao1_caic2024&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=JoseHenao1_caic2024)
[![CI/CD Pipeline](https://github.com/JoseHenao1/caic2024/actions/workflows/build.yml/badge.svg)](https://github.com/JoseHenao1/caic2024/actions/workflows/build.yml)

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
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
