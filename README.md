# RuM as dependency (minified)

## Requirements

- Java JDK 11

## Compile

- Run `mvn dependency:purge-local-repository -DactTransitively=false -DreResolve=false` to clean dependencies cache stored in .m2 hidden folder

- Run `mvn clean package` to create minified package in `/target` folder

## Origin

Forked from <https://bitbucket.org/doorless1634/thesis/src/master>
