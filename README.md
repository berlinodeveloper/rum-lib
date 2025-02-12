# RuM as dependency

## Description

This repository contains the code from the RuM application without the UI only for the purpose to export a minified package to use in other programs

## Requirements

- Java JDK 11
- Apache Maven Build Tool

## Compile

- Run `mvn dependency:purge-local-repository -DactTransitively=false -DreResolve=false` to clean dependencies cache stored in .m2 hidden folder

- Run `mvn clean package` to create `rum-0.6.10-lib.jar` package in`/target` folder

## Origin

Forked from <https://bitbucket.org/doorless1634/thesis/src/master>
