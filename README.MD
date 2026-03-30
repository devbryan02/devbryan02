# Brayan Cárdenas Muñoz
**Analista Programador Junior | Java Backend Developer**

Estudiante de último ciclo de Ingeniería de Sistemas en Ayacucho, Perú, con experiencia desarrollando y desplegando APIs REST para el sector público. Especializado en Java y Spring Boot (incluyendo enfoques reactivos), aplicando Arquitectura Hexagonal, SOLID y Clean Code para construir software mantenible, escalable y fácil de evolucionar.

---

## Perfil
- Desarrollo de APIs REST y servicios backend con Java y Spring (Spring Boot / WebFlux).
- Diseño orientado a dominio con Arquitectura Hexagonal y principios SOLID.
- Seguridad aplicada con Spring Security y JWT, control de roles y buenas prácticas.
- Persistencia de datos con PostgreSQL (incluyendo R2DBC cuando aplica).
- Pruebas unitarias con JUnit 5 y Mockito.
- Contenerización y despliegue con Docker; migraciones con Flyway.

---

## Stack tecnológico
- **Lenguaje:** Java  
- **Frameworks:** Spring Boot, Spring WebFlux, Spring Security  
- **Persistencia:** PostgreSQL, R2DBC  
- **Testing:** JUnit 5, Mockito  
- **DevOps / Deploy:** Docker, Flyway, Railway  

---

## Proyectos destacados

### Sistema de Gestión de Mascotas – Municipalidad A.A. Cáceres
Repositorio: https://github.com/devbryan02/veterinaria-app-backend  
Estado: Producción

API REST reactiva para la gestión de salud animal municipal.

**Aportes y características:**
- Núcleo basado en **Arquitectura Hexagonal**, con enfoque **CQRS** y auditoría automática mediante **AOP**.
- Implementación con **Spring WebFlux**, **R2DBC** y **PostgreSQL**.
- Exportación de reportes (Excel).
- Autenticación y autorización con **Spring Security + JWT**, manejo de roles.
- Pipeline de despliegue con **Docker**, migraciones con **Flyway** y publicación en **Railway**.

---

### Hotel SaaS – Gestión Multi-Tenant
Repositorio: https://github.com/devbryan02/hotel-saas  

Sistema de gestión hotelera con aislamiento de datos por cliente (multi-tenant).

**Aportes y características:**
- API REST multi-tenant con módulos de habitaciones, clientes y ocupaciones (check-in / check-out).
- **Arquitectura Hexagonal** y manejo centralizado de excepciones de dominio.
- Pruebas unitarias con **JUnit 5** y **Mockito** en casos críticos (por ejemplo, `CheckOutOccupationUseCase`).

---

### Generador de Horarios Académicos
Repositorio: https://github.com/devbryan02/asignacion-de-horario  

Motor de optimización para asignación automática de recursos académicos.

**Aportes y características:**
- Optimización con **OptaPlanner** para restricciones de docentes, aulas y secciones.
- Backend con Spring Boot.
- Frontend con **React + TypeScript** (DaisyUI).

---

## Contacto
- GitHub: https://github.com/devbryan02

---

## Estado profesional (snippet)
```java
@Builder
@Slf4j
public class Developer {
    private final String name      = "Brayan Cárdenas Muñoz";
    private final String role      = "Analista Programador Junior | Java Backend Developer";
    private final String location  = "Ayacucho, Perú";
    private final String languages = "Español (Nativo), Quechua (Nativo), Inglés (Técnico)";

    public void displayStatus() {
        log.info("Status: Open to work | Ready to build scalable APIs");
    }
}
```
