# Spring Boot v3 Intregação com Keycloak 

Projeto de demonstração para integração do Keycloak com Spring Boot 3

### Endpoints
Anonymous:
```
[GET] http://localhost:8081/api/test/anonymous
```
Admin:
```
[GET] http://localhost:8081/api/test/admin
Authorization - Bearer Token with admin privileges
```
User:
```
[GET] http://localhost:8081/api/test/user
Authorization - Bearer Token with admin or user privileges
```
