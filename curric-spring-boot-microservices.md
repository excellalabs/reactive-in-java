### Distributed Systems & Microservices

## NOTE: THIS HAS A LOT OF WORK AND CLEANING UP NEEDED

- 12 Factor App
- [Distributed Systems in One Lesson](https://learning.oreilly.com/videos/distributed-systems-in/9781491924914?autoplay=false)
    - IaaS, CaaS, PaaS, SaaS
- Integration Patterns
- [Microservices Patterns](https://learning.oreilly.com/library/view/microservices-patterns/9781617294549/)
- Testing
    - Test pyramid to honeycomb: more integration tests, [Testing Microservices at Spotify](https://labs.spotify.com/2018/01/11/testing-of-microservices/)
    => Exercise: TODO
- Monitoring
    [ ] Using New Relic
- Tracing
- Logging
- Choreographing Microservices
        Deployment and scaling techniques
        Service Discovery (i.e. with Eureka and Consul)
        Client routing (i.e. Ribbon)
        Prevent failure cascades (i.e. Hystrix)
        Circuit breakers to isolate failure
        Smart proxy: connect web clients to backend services with Zuul 

- Scaling
- Clustering
- Load Balancing
- Databases: Scaling, horizontal and vertical, database pools, load balancing, partitioning, data tier 1st and 2nd level caching
- Application-tier caching: memcached, redis
- Distributed caching

### Spring & Spring Boot

- [Docs](https://spring.io/guides/gs/spring-boot/)
- [Microservices with Spring Boot (video)](https://learning.oreilly.com/videos/building-microservices-with/9780134678658?autoplay=false)
- TOPICS
    - [Bean Lifecycle (video)](https://learning.oreilly.com/videos/spring-5-0-project/9781787284210/9781787284210-video2_1)
    - Aspect-Oriented (AspectJ, auditing, security)
    - Logging
        - Overview
        - [Code](https://github.com/livelessons-spring/building-microservices/tree/master/livelessons-operations/livelessons-operations-logging )
    - Security
        - [Code](https://github.com/livelessons-spring/building-microservices/tree/master/livelessons-security)

- Key libraries
    - Reactor for reactive functional programming
    - Spring Data JDBC
    - Flyway for Database Migrations
    - PostgreSQL in a container for local development
    - Lombok
    - Checkstyle
    - Spring Actuator
    - JUnit

- Threads, connection pools
    - Lifecycle, beans
    - Automated testing
        - Integration testing annotations, etc.
    - ... TBD

### Exercises

- TODO: exercises/app (can go right with the topic)
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





SORT:

*Concepts*

    Spring Boot
        Fundamentals
        Building with Maven, Gradle, POMs, fat jars, auto-configuration
        
        Map configuration properties to POJOs, relaxed binding
        Centalize configuration (i.e. Spring Cloud Server)
        Profiles for multiple environments

        Key annotations

            @Bean, Component
            @Scheduled
    Data
        Spring Data
        Flyway

    Ops-Friendly Microservices
        Spring Boot Actuator
        
    Integration and Batch Processing
        Batch Data Processing with Spring Batch
        Spring Cloud
        Enterprise Integration Patterns
        CQRS to connect microservices
        Implicit integration: channels in Spring Cloud Stream (let it do wiring and binding)

    Web Applications in Microservices
        Serving
        Templating with Thymleaf
        Resolve and transform resources
        HTTP compression, caching

    Securing Microservices
        Auth
        Spring security
        SSL/TLS and x509 mutual authentication
        Problems with passwords and certificates
        OAuth for single sign-on, JWTs








## COURSE: Building Microservices with Spring Boot
Phil Webb (co-creator of Spring Boot), Josh Long (Spring Developer Advocate at Pivotal and a Java Champion)

If you are interested in a brown bag lunch (12:00-1:00) once-a-week, to watch the microservices part of the [*Microservices in Spring Boot*](https://learning.oreilly.com/videos/building-microservices-with/9780134192468/9780134192468-01_09) course taught by Spring Boot co-creator Phil Webb, and Java Champion John Long at Pivotal on Safari Books online of which I have a subscription to, please vote for which days you can do. It's specifically the last half where the Spring Boot for microservices content starts (the previous lessons are mostly on just Spring Boot).

It goes over the entire landscape, giving insights from these insiders that will fill in gaps and give understanding to the all of the foundational concepts to really leverage Spring Boot for microservices from circuit breaks and monitoring to cascading failures and OAuth. In 4 lunches (12:00-1, brown bag) we can cover the below agenda.

I am not sure if there will be an app to follow along with since it goes fast, but we could consider extending to more lunches to make time to code up what they're teaching. It is important to practice many of the concepts to solidify the skill.

LUNCH 1
    Reactive Springt
    Project Reactor


    Integration and Batch Processing
        *Batch Data Processing with Spring Batch
        Spring Cloud
        Go Beyond RESTFul Microservices
        Understand "Enterprise Integration Patterns"
        Use CQRS to connect microservices

        Implicit integration with channels in Spring Cloud Stream (let it do wiring and binding)

LUNCH 2
    Creating Ops-Friendly Microservices
        Understand the implication of agile methodologies on operations
        Gain insight via logging
        Introduce Spring Boot Actuator
        Monitor Microservices
        Diagnose errors

LUNCH 3
    Choreographing Microservices
        Understand deployment and scaling techniques
        Discover and register services with Eureka and Consul
        Route on the client with Ribbon
        Prevent failure cascades with Hystrix
        Isolate failures using circuit breakers
        Connect web clients to backend services with Zuul   

LUNCH 4
    Web Applications in Microservices
        Serving
        Templating with Thymleaf
        Resolve and transform resources

    Securing Microservices
        Spring security
        SSL/TLS and x509 mutual authentication
        Problems with passwords and certificates
        OAuth for single sign-on



Lunch 1: Spring Session, Spring Cloud AWS, Enterprise integration pattern, batch processing, CQRS

Lunch 2: Creating ops-friendly microservices, implications of agile on operations, logging, monitoring, diagnosing errors

Lunch 3: Choreographing microservices, service discovery and r                                                                                                                                                                                                                                                                                                                                                                                                                                    egistration, routing, preventing failure cascades, isolate failures with circuit breakers, connecting to the backend

Lunch 4: Web applications in microservices, Spring security, SSL/TLS and x509 mutual, authentication, OAuth
