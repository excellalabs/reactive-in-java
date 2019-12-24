# Java Foundation for Reactive

This curriculum will review modern approaches in Java that reactive programming builds on. 

1. Review [Modern Java Crash Course](#Modern-Java–Crash-Course), which includes learning resources, libraries, and key concepts.
1. Go through the [Reactive and Reactor Curriculum](#Reactive-and-Reactor-Curriculum)

# Modern Java Crash Course

This areas should be covered or brushed up on before expanding into reactive programming with Reactor, including lambdas, streams, and functional. These features really started showing up in Java 8, are an important foundation to reactive. 

- [ ] [Streams in Java](https://stackify.com/streams-guide-java-8/) (30m)
- [ ] [Learning Modern Java](https://learning.oreilly.com/videos/learning-modern-java/9780134383613?autoplay=false) (video)
  - [ ] Sections on Lambdas, Streams, Optional, Reactive Streams & Reactor, Reactive data
  - [ ] Any other section you need to review
- [ ] [Functional Programming for Java](https://learning.oreilly.com/videos/functional-programming-for/9780134778235?autoplay=false) (video)
    
## Common Libraries in Java

- Spring Data JDBC
- SLF4J, Logback
- Swagger
- JUnit
- Mockito
- Lombok
- Vavr

## Key Concepts

These are the concepts that we will dive into the learning materials below. You should understand all of them after going through the learn materials.

- Reactive
    - *Reactive defined:* Composable asynchronous implementing the [Reactive Streams](http://www.reactive-streams.org/) specification
    - Streams, event loop
    - Other tools to reduce complexity of concurrency under load: java.util.concurrent, Akka streams, CompletableFuture, and frameworks like Netty
    - Patterns: Higher order functions, currying, etc.
- The Reactive Streams Spec
- Core Operators (map, flatMap, filter, buffer)
- Project Reactor
  - Flux and Mono
  - the Spring-Webflux Module

# Reactive and Reactor Curriculum

Now we get into the reactive area, guided by the Reactive Manifesto, in this case is implemented with Reactor (RxJava would be the main competitor). 

## Reactor Learning Resources

This will set the foundation of functional reactive programming with Reactor and will provide the bulk of what you need to get started.

It's very important to try out as much as you can as you go along, for everything to make sense and sink in. You should **start up a project with Reactor** so you can start coding right away. Here is a [minimal working template](https://github.com/Wyntuition/spring-reactor-template) if you want a jumpstart. The **exercises** below can also be done along the way.

- [ ] [Reactive 3 Overview, with Simon Basle (video, 51m)](https://www.youtube.com/watch?v=WJK6chc7w3o)
- [ ] [Reactor by Example on InfoQ - quick dive](https://www.infoq.com/articles/reactor-by-example)
- [ ] [Reactor Reference Guide & Docs](https://projectreactor.io/docs/core/release/reference/)
    - [ ] Read first part which explains Reactor and become generally familiar
    - [ ] Review important references including [When to use what operator](https://projectreactor.io/docs/core/release/reference/index.html#which-operator) - appendix to the Reference Guide that is very helpful

**Exercises**

- [ ] [Reactor's Learning Material](https://projectreactor.io/learn)
- [ ] [Set up Reactor with Spring Data](https://spring.io/blog/2016/11/28/going-reactive-with-spring-data)
