# Spring Boot Eureka Server

Basically nothing more than an empty Spring Boot app with `@SpringBootApplication` and a few properties to support a standalone mode.

## Push Docker Image

```
docker login registry-1.docker.io # without the explicit host, we get an authentication error

./gradlew jib
```
