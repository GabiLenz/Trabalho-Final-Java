# Atividade Final do Semestre - Arquitetura de Microserviços

Este repositório contém a implementação dos microserviços utilizando Docker e Eureka, além de um API Gateway para roteamento de requisições. Os serviços envolvidos são:

## Serviços Implementados

- 🔄 **cambio-service**
- 📦 **produto-service**
- 💬 **saudacao-service**
- 🛠 **config-service**
- 📡 **eureka-service**
- 🌐 **api-gateway-service**

## Docker Compose
O arquivo `docker-compose.yml` contém os seguintes serviços:
- **eureka-service**
- **cambio-db** e **cambio-service**
- **produto-db** e **produto-service**
- **api-gateway-service**


## Tecnologias Utilizadas
- Java
- Spring Boot
- Spring Cloud
- Netflix OSS Eureka
- Docker
- Postman
