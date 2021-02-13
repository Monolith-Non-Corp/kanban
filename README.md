# Kanban

Kanban docker-compose rules to containerize [kanban-client](https://github.com/Monolith-Non-Corp/kanban-client) and [kanban-server](https://github.com/Monolith-Non-Corp/kanban-server) with its dependencies.

## How to use

### With Git and Docker

- Clone the [git repository]().
- Imagerize [kanban-server](https://github.com/Monolith-Non-Corp/kanban-server) with the [Spring Boot Buildpack](https://spring.io/blog/2020/01/27/creating-docker-images-with-spring-boot-2-3-0-m1).
- Containerize docker-services.yml with docker-compose and configure Keycloak
- Containerize docker-compose.yml with docker-compose.
- Browse localhost:3000
