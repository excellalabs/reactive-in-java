# Java Foundation for Reactive

This curriculum will review modern approaches in Java that reactive programming builds on. 

1. Review [Modern Java Crash Course Curriculum](#Modern-Java–Crash-Course-Curriculum), which includes learning resources, libraries, and key concepts.
1. Go through the [Reactive and Reactor Curriculum](#Reactive-and-Reactor-Curriculum)

# Modern Java Crash Course Curriculum

This areas should be covered or brushed up on before expanding into reactive programming with Reactor, including lambdas, streams, and functional. These features really started showing up in Java 8, are an important foundation to reactive. 

1. The book [Modern Java in Acton](https://www.manning.com/books/modern-java-in-action) covers all modern approaches, including lambdas, streams, and reactive. 

*OR*

1. [Streams in Java](https://stackify.com/streams-guide-java-8/) (30m)
1. [Learning Modern Java](https://learning.oreilly.com/videos/learning-modern-java/9780134383613?autoplay=false) (video)
    1. Sections on Lambdas, Streams, Optional, Reactive Streams & Reactor, Reactive data
    1. Any other section you need to review
1. [Functional Programming for Java](https://learning.oreilly.com/videos/functional-programming-for/9780134778235?autoplay=false) (video)
    
## Common Libraries in Java

Be familiar with core libraries for common Java apps that you will encounter:

- Spring Data JDBC
- SLF4J, Logback
- Swagger
- JUnit
- Mockito
- Lombok
- Vavr

## Key Concepts

Review these concepts. They are what will be covered below. You should understand all of them after going through the learn materials:

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

Now we get into the reactive area, guided by the Reactive Manifesto, in this case is implemented with Reactor (RxJava would be the main competitor). This will set the foundation of functional reactive programming with Reactor and will provide the bulk of what you need to get started.

Go through the materal below, which covers everything you need to get going with reactive programming in Java using Reactor.

It's very important to try out as much as you can as you go along, for everything to make sense and sink in. You should **start up a project with Reactor** so you can start coding right away. Here is a [minimal working template](https://github.com/Wyntuition/spring-reactor-template) if you want a jumpstart. The **exercises** below can also be done along the way.

1. [Reactive 3 Overview, with Simon Basle (video, 51m)](https://www.youtube.com/watch?v=WJK6chc7w3o)
1. [Reactor by Example on InfoQ - quick dive](https://www.infoq.com/articles/reactor-by-example)
1. [Reactor Reference Guide & Docs](https://projectreactor.io/docs/core/release/reference/)
    1. Read first part which explains Reactor and become generally familiar
    1. Review important references including [When to use what operator](https://projectreactor.io/docs/core/release/reference/index.html#which-operator) - appendix to the Reference Guide that is very helpful

**Exercises**

1. [Reactor's Learning Material](https://projectreactor.io/learn)
1. [Set up Reactor with Spring Data](https://spring.io/blog/2016/11/28/going-reactive-with-spring-data)
