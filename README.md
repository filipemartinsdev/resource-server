# Spring Boot Resource Server


This is a template that setups an application to get authentication from external Identity Provider (Auth0).

---

## Stack

- Java 21
- Spring Boot 4.x
- OAuth Resource Server
- Auth0 IDP
- Docker & Docker Compose

---

## How to execute


### Prerequisits
- Docker

### Executing

1. Create and fill the `.env` file
    
    ````bash
    cp .example.env .env
    ````

2. Execute with Docker
    
    ````bash
    docker compose up --build
    ````

---
