# DeployServer

A sample implementation for using GitHub Deployment API.

Ported [this](https://developer.github.com/guides/delivering-deployments/) by Java. Powerd by [Spark](http://sparkjava.com/).

## Prerequisite
- JDK8
- Maven3

## Getting Started
- For development
```
$ mvn compile exec:java
```

- For deployment
```
$ mvn clean package
$ java -jar target/DeployServer-{version}.jar
```

Then you can see the result on `http://localhost:4567`.

## TODO:
- [ ] Write how to setup with IDEA and Eclipse and how to run it
- [x] Write how to package it