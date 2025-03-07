# localhost.run Spring Boot Starter

Spring Boot Starter to share your localhost Spring Application with an external url.

## What is localhost.run?

localhost.run is an SSH server just for remote port forwarding. When a user connects to localhost.run, they get a public URL that anybody can use to connect to their localhost server.

## How works this starter?

When you add this dependency to your pom.xml and configure it, you'll automatically get a public url to your local server.

 ## Dependency
 
Actual version is 2.0
 
 * Maven:
 ```xml
<dependency>
    <groupId>com.github.migangqui</groupId>
    <artifactId>localhost-run-spring-boot-starter</artifactId>
    <version>2.0</version>
</dependency>
```

* Gradle:
 ```groovy
compile('com.github.migangqui:localhost-run-spring-boot-starter:2.0')
```

https://mvnrepository.com/artifact/com.github.migangqui/localhost-run-spring-boot-starter

## Configuration

You must enable localhost.com runner adding the following property:
```yaml
localhost-run:
    enabled: true
```

### References

* Based in similar ngrok starter: https://github.com/kilmajster/ngrok-spring-boot-starter
* http://serveo.net/#manual