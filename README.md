# Curricula: Reactive Programming with Reactor and Spring Boot, and Related Material

Curriculum for learning reactive programming in Java, specifically with Spring Boot and Reactor, with a front-end in React

This will probably be broken up into subpages by the `Curricula` sections, but for now we're trying to get key topics enumerated so people are aware of the landscape they need to know, with key resources to go through (in minimal amount of time), and eventually exercises / app to build to reinforce learning (NOTE: repo is poorly named right as now as it started out focused on reactive).

NOTE: A lot of these resources come from Safari, which requires a subscription which is highly recommended (trials available).

## [TODO](todo.md)

## Curricula Overview

* Getting Started with Reactor
  * Basics of streams, event loop
  * Reactor
  * Fluxes and Monos
  * Operators
  * Patterns: Higher order functions, currying, etc.
  * Use cases for Reactor approaches (i.e. zips, tuples)
* Spring Boot
* Java language, patterns and architecture
* Distributed Systems
* Front-end with React

# Getting Started with Reactor

## Learning 

- [Reactive in Spring (video)](https://learning.oreilly.com/videos/reactive-spring/9781492025733/9781492025733-video317125) - This has about **40 minutes** of video going over reactive and how Reactor is the default implementation in spring boot, and then gets into it. It's a good place to start, to get an overview. Key sections: 
  - The Reactive Streams Spec
  - Project Reactor
  - Flux and Mono
  - Using the Flux and Mono Methods
  - Reactive Streams and the Spring-Webflux Module

- Read through the [Reactor Reference Guide & Docs](https://projectreactor.io/docs/core/release/reference/) - this is a key resource to learning Reactor, with the needed depth
  
  Additional key materials from the docs:
  - [When to use what operator](https://projectreactor.io/docs/core/release/reference/index.html#which-operator) - appendix to the Reference Guide that is very helpful
  - [Reactor's Learning Material](https://projectreactor.io/learn) - material they provide to learn, including exercises

## Doing

- TODO: exercises/app

# Spring Boot

## Learning

- [Docs](https://spring.io/guides/gs/spring-boot/)
- [Microservices with Spring Boot](https://learning.oreilly.com/videos/building-microservices-with/9780134678658?autoplay=false)
- TOPICS
    - [Bean Lifecycle](https://learning.oreilly.com/videos/spring-5-0-project/9781787284210/9781787284210-video2_1)
    - Aspect-Oriented (AspectJ, auditing, security) - TODO
    - TODO
- Key libraries
    - Reactor for reactive functional programming
    - Spring Data JDBC
    - Flyway for Database Migrations
    - PostgreSQL in a container for local development
    - Lombok
    - Checkstyle
    - Spring Actuator
    - JUnit

## Doing

* [Validating Form Input](https://spring.io/guides/gs/validating-form-input/)
* [Securing a Web Application](https://spring.io/guides/gs/securing-web/)
* [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
* [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/)
* [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/)
* [Integrating Data](https://spring.io/guides/gs/integration/)
* [Messaging with RabbitMQ](https://spring.io/guides/gs/messaging-rabbitmq/)
* [Routing and Filtering](https://spring.io/guides/gs/routing-and-filtering/)
* [Using Spring Cloud Gateway](https://github.com/spring-cloud-samples/spring-cloud-gateway-sample)
* [Client Side Load Balancing with Ribbon and Spring Cloud](https://spring.io/guides/gs/client-side-load-balancing/)
* [Circuit Breaker](https://spring.io/guides/gs/circuit-breaker/)
* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)

* [Various sample apps using Spring Cloud Function](https://github.com/spring-cloud/spring-cloud-function/tree/master/spring-cloud-function-samples)



# Java

## Learning 

- Modern Java (8, 11, streams, lambdas, etc)
    - [Learning Modern Java](https://learning.oreilly.com/videos/learning-modern-java/9780134383613?autoplay=false)
    - [Lambdas, Streams, Optional, Reactive Streams & Reactor, Reactive data](https://learning.oreilly.com/videos/reactive-spring/9781492025733/9781492025733-video317119)
    - [Functional](https://learning.oreilly.com/videos/functional-programming-for/9780134778235?autoplay=false)
    - [Set up Reactor with Sprint Data](https://spring.io/blog/2016/11/28/going-reactive-with-spring-data)
    - [Example use with business objects, Integrating Reactor with Spring and Creating Reactive Code](https://learning.oreilly.com/videos/spring-5-0-project/9781787284210/9781787284210-video5_1)
- Patterns
  - [Effective Java](https://learning.oreilly.com/library/view/effective-java-2nd/9780137150021/) - cornerstone book on the right way to write Java
- Architecture - TODO

## Doing

- TODO: exercises/app

# Distributed Systems

## Learning

- Integration Patterns - TODO
- [Distributed Systems in One Lesson](https://learning.oreilly.com/videos/distributed-systems-in/9781491924914?autoplay=false)
- [Microservices Patterns](https://learning.oreilly.com/library/view/microservices-patterns/9781617294549/)

## Doing

- TODO: exercises/app

# React

## Learning

- [Hands-on Web Development with React](https://learning.oreilly.com/videos/hands-on-web-development/9781789343915?autoplay=false)

## Doing

- TODO: exercises/app
