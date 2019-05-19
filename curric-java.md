# Reactive with Reactor in Java

## Overview

Curriculum for learning reactive programming in Java, specifically with Spring Boot and Reactor

## Java Foundation for Reactive

### Modern Java (streams, lambdas, etc)

- [ ] [Learning Modern Java](https://learning.oreilly.com/videos/learning-modern-java/9780134383613?autoplay=false)
- [ ] [Lambdas, Streams, Optional, Reactive Streams & Reactor, Reactive data](https://learning.oreilly.com/videos/reactive-spring/9781492025733/9781492025733-video317119)
- [ ] [Functional](https://learning.oreilly.com/videos/functional-programming-for/9780134778235?autoplay=false)

**Exercises**
- [ ] TODO
- [ ] Guided creation of a an app - [Example use with business objects, Integrating Reactor with Spring and Creating Reactive Code](https://learning.oreilly.com/videos/spring-5-0-project/9781787284210/9781787284210-video5_1)
    
### Foundation Java Review

- [Effective Java](https://learning.oreilly.com/library/view/effective-java-2nd/9780137150021/) - cornerstone book on the right way to write Java
- Patterns
- Error handling
- Architecture
- DI
- AOP
- Language constructs
  - Optional
  - //TODO
- IDE setup & IntelliJ Overview
- Dependency Management
- Nexus
    
### Libraries

- Spring Data JDBC
- JAXRS
- Logback
- SLF4J, Logback
- Swagger
- Junit
- Mockito
- Lombok

**Exercise**

[ ] App that uses the above libraries

# Reactive and Reactor Curriculum
  
Key Concepts:

- Reactive
    - **Reactive** Composable asynchronous implementing the [Reactive Streams](http://www.reactive-streams.org/) specification
    - Basics of streams, event loop
    - Other tools to reduce complexity of concurrency under load: java.util.concurrent, Akka streams, CompletableFuture, and frameworks like Netty
    - Patterns: Higher order functions, currying, etc.
- The Reactive Streams Spec
- Project Reactor
- Flux and Mono
- Using the Flux and Mono Methods
- Reactive Streams and the Spring-Webflux Module
- Core Operators
    - mapTry
    - filter
    - onSuccess, onFailure
    - toCompleteableFuture

### Learning Resources

- [ ] [Reactor by Example on InfoQ](https://www.infoq.com/articles/reactor-by-example)
- [ ] [Reactor Reference Guide & Docs](https://projectreactor.io/docs/core/release/reference/)
    - [ ] Read first part which explains Reactor

**Exercise**
- [ ] [Set up Reactor with Sprint Data](https://spring.io/blog/2016/11/28/going-reactive-with-spring-data)
- [ ] [When to use what operator](https://projectreactor.io/docs/core/release/reference/index.html#which-operator) - appendix to the Reference Guide that is very helpful

- [ ] [Reactive in Spring (video)](https://learning.oreilly.com/videos/reactive-spring/9781492025733/9781492025733-video317125) - This has about **40 minutes** of video going over reactive and how Reactor is the default implementation in spring boot, and then gets into it. It's a good way to get a video overview.
- [ ] [Reactive 3, deeper with Simon Basle (video, 51m)](https://www.youtube.com/watch?v=WJK6chc7w3o)
- [ ] [Reactor's Learning Material](https://projectreactor.io/learn)
