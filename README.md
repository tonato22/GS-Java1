﻿# API de Apoio Psicológico Remoto

Este projeto é uma API REST desenvolvida em Java 17 com Spring Boot, destinada ao gerenciamento de usuários, agendamentos e relatórios de apoio psicológico em contextos de calamidade.

## ✅ Requisitos

- Java 17
- Maven 3.8+
- PostgreSQL
- IDE recomendada: IntelliJ IDEA ou VSCode

---

## ⚙️ Tecnologias e Recursos

- ✅ Spring Boot 3.2.5
- ✅ Spring Data JPA
- ✅ PostgreSQL
- ✅ Spring Security + JWT
- ✅ Bean Validation
- ✅ Swagger UI (OpenAPI 3)
- ✅ CORS Configurado
- ✅ Deploy pronto para nuvem

---

## 🔧 Configuração do Banco

**application.properties:**

```properties
spring.datasource.url=jdbc:postgresql://interchange.proxy.rlwy.net:35713/railway
spring.datasource.username=postgres
spring.datasource.password=lhlcRsXWTwRElGBSTlAtkqaWoaGicykF
spring.datasource.driver-class-name=org.postgresql.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect

springdoc.api-docs.path=/api-docs
