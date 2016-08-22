# Simple Zipkin server application using Spring Boot

<a href='https://travis-ci.org/iancollington/zipkin-server/builds'><img src='https://travis-ci.org/iancollington/zipkin-server.svg?branch=master'></a>

Generic implementation of a Zipkin server using Spring Boot that can be used for any application. Just point your application at the running Zipkin instance via the application.properties file:

```
spring.zipkin.baseUrl=http://localhost:8080/
```
