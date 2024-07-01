# Dapr Actor Java

### Maven
```
mvn install
```

### Run Server

```
dapr run --components-path ./components --app-id demo-actor-server --app-port 8080 -- java -jar target/dapr-actor-demo-1.0.0.jar;
```

### Run client
```
dapr run --components-path ./components --app-id actor-client -- mvn compile exec:java -Dexec.mainClass="io.github.wynn5a.DemoActorClient";`
```
