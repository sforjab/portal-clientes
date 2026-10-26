# Portal de Clientes

API REST de gestión de clientes construida con Spring Boot, Spring Data JPA y
una base de datos H2 en memoria. Implementa un CRUD básico de `Cliente` y sirve
como proyecto base del curso *Claude Code y Alternativas IA para Desarrolladores
Java*.

## Cómo arrancar la aplicación

```bash
mvn spring-boot:run
```

La API queda disponible en `http://localhost:8080/clientes`. La consola de H2
está en `http://localhost:8080/h2-console` (JDBC URL: `jdbc:h2:mem:demodb`).

## Cómo ejecutar los tests

```bash
mvn test
```

## Convenciones del equipo

Las convenciones de arquitectura, acceso a datos, manejo de errores, testing y
seguridad que este proyecto sigue están definidas en [CLAUDE.md](CLAUDE.md).
Claude Code debe leer y respetar ese fichero al trabajar en este repositorio.
