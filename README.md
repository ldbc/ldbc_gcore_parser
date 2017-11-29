# GCORE Grammar and Parser

A repository to work towards an open-source grammar for the property graph query language developed by the LDBC Graph Query Language Task Force.  Started on 29 August 2017, as an outcome of an all-hands Task Force meeting in Santiago de Chile earlier in the month.

## Building the Parser

```bash
export MAVEN_OPTS="-Xms512m -Xmx1024m -Xss16m"
cd gcore-spoofax/
mvn clean install
```

## Running the Unit Tests

```bash
cd gcore-spoofax-tests/
mvn test
```
