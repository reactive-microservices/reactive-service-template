# Reactive microservice example using Vert.x.


## Unit tests.

```
mvn clean test
```

## Integration tests

```
mvn clean test -P integration
```

## Run locally

Using maven:
```
mvn compile exec:java
```
Using fat jar file:
```
java -jar target/reactive-service-template-1.0.0-SNAPSHOT-fat.jar
```

Check service running:
```
curl localhost:7777
```

## Related project

https://github.com/redhat-developer/reactive-microservices-in-java
