# Auth Service - Mi Perfumería

Microservicio de autenticación y autorización para la aplicación Mi Perfumería.

> 📦 Parte del proyecto [Mi Perfumería](https://github.com/HarolC17/mi-perfumeria-app)

## Descripción

Servicio encargado de gestionar el registro, inicio de sesión y autorización de usuarios mediante roles (USER, ADMIN).

## Tecnologías

- Java 17
- Spring Boot 3.x
- Spring Security
- PostgreSQL / MySQL
- REST API

## Endpoints

| Método | Endpoint | Descripción | Acceso |
|--------|----------|-------------|--------|
| POST | `/auth/register` | Registrar nuevo usuario | Público |
| POST | `/auth/login` | Iniciar sesión | Público |

## Roles

- **USER:** Acceso a carrito y órdenes propias
- **ADMIN:** CRUD completo en todos los servicios

## Instalación

git clone https://github.com/HarolC17/auth-service.git
cd auth-service
