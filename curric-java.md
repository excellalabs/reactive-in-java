# Java Foundation for Reactive

## Modern Java (streams, lambdas, etc)

- [Learning Modern Java](https://learning.oreilly.com/videos/learning-modern-java/9780134383613?autoplay=false)
  - [ ] Sections on Lambdas, Streams, Optional, Reactive Streams & Reactor, Reactive data
  - [ ] Any other section you need to review
- [ ] [Functional Programming for Java](https://learning.oreilly.com/videos/functional-programming-for/9780134778235?autoplay=false)

**Exercises**
- [ ] TODO
    
## Foundational Java Review

- Patterns
  - [ ] [Effective Java](https://learning.oreilly.com/library/view/effective-java-2nd/9780137150021/) - cornerstone book on the right way to write Java
- // TODO resource for the below, esp. IDE setup for efficiency
- Error handling
- Architecture
- DI
- IDE setup & IntelliJ Overview
- Dependency Management
- Nexus
    
## Libraries

- Spring Data JDBC
- SLF4J, Logback
- Swagger
- JUnit
- Mockito
- Lombok

**Exercise**

- [ ] App that uses the above libraries

# Reactive and Reactor Curriculum
  
## Key Concepts

Review these concepts. You should understand all of them after going through the learn materials below.

- Reactive
    - *Reactive defined:* Composable asynchronous implementing the [Reactive Streams](http://www.reactive-streams.org/) specification
    - Streams, event loop
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
    - //TODO

## Learning Resources

### Part 1 

- [ ] [Reactor by Example on InfoQ](https://www.infoq.com/articles/reactor-by-example)
- [ ] [Reactor Reference Guide & Docs](https://projectreactor.io/docs/core/release/reference/)
    - [ ] Read first part which explains Reactor
- [ ] [Reactive in Spring (video)](https://learning.oreilly.com/videos/reactive-spring/9781492025733/9781492025733-video317125) - This has about **40 minutes** of video going over reactive and how Reactor is the default implementation in spring boot, and then gets into it. It's a good way to get a video overview.

**Exercises**

- [ ] [Reactor's Learning Material](https://projectreactor.io/learn)
- [ ] [Set up Reactor with Spring Data](https://spring.io/blog/2016/11/28/going-reactive-with-spring-data)

### Part 2

**Learning Material**

- [ ] [When to use what operator](https://projectreactor.io/docs/core/release/reference/index.html#which-operator) - appendix to the Reference Guide that is very helpful
- [ ] [Reactive 3, deeper with Simon Basle (video, 51m)](https://www.youtube.com/watch?v=WJK6chc7w3o)

**Exercises**

- [ ] Guided creation of a larger app - [Example use with business objects, Integrating Reactor with Spring and Creating Reactive Code](https://learning.oreilly.com/videos/spring-5-0-project/9781787284210/9781787284210-video5_1)

