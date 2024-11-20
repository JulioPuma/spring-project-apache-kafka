#  Spring Project for Apache Kafka

Project using docker, springboot and service to manage events like Apache Kafka.

* Language: Java 17 
* Framework: SpringBoot 3
* Dependency management: Maven 3.6.3

<img src="./docs/markdown/java17-logo.png" style="height: 50px; width:100px;"/>
<img src="./docs/markdown/springboot.png" style="height: 50px; width:100px;"/>

## Dependencies

- spring-boot-starter
- spring-kafka
- lombok

## Package

- controllers: Used to define endpoints.
- service: Used to process logic bussines.
- repository: Used to connect with relational databases .
- proxy.client: Implements Classes to connect with other REST Services.
- config: Used to configure the project behaviour. 
- model: Used to create simples object like POJOs, DTOs. 