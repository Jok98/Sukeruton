# Sukeruton

It's an architectural skeleton for Java microservices projects using Spring Boot, Docker, and Kubernetes.

The goal is to reduce development time by providing a stable architectural foundation—complete, allowing developers to
focus primarily on implementing business logic.

## Features

| Tech                               | Impl. Tool                                      |
|------------------------------------|-------------------------------------------------|
| API Gateway                        | Spring Cloud Gateway                            |
| Service Discovery                  | Netflix Eureka                                  |
| Centralized configuration          | Spring Cloud Config                             |
| Circuit Breaker                    | Resilience4j                                    |
| Asynchronous Communication         | Apache Kafka                                    |
| Distributed Logging and Tracing    | Spring Cloud Sleuth                             |
| Security                           | Spring Security with support for OAuth2 and JWT |
| Containerization and Orchestration | Docker, Kubernetes                              |
| Testing and CI/CD                  | JUnit, Mockito, Jenkins, GitHub Actions         |
| Monitoring and Alerting            | Prometheus                                      |