<div align="center">

# `> Brayan Cárdenas Muñoz`

**Java Backend Developer · Ayacucho, Perú 🇵🇪**

*Construyo APIs que escalan — con arquitectura limpia, seguridad robusta y código que habla por sí solo.*

[![GitHub](https://img.shields.io/badge/GitHub-devbryan02-181717?style=flat-square&logo=github)](https://github.com/devbryan02)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=flat-square)]()
[![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)]()
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)]()

</div>

---

## Proyectos destacados

### [Hotel SaaS — API Multi-Tenant](https://github.com/devbryan02/hotel-saas-back)
> Backend completo para gestión hotelera con soporte multi-tenant orientado al mercado de Ayacucho.

**Stack:** Java 21 · Spring Boot 4 · PostgreSQL + JPA · Flyway · JWT (claims tenantId) · RBAC · Docker Compose · Prometheus · Grafana · Bucket4j

- Arquitectura Clean/Hexagonal con capas `domain → application → infrastructure → web`
- Seguridad stateless con JWT y control de acceso por roles configurado por rutas
- Observabilidad completa: Actuator + Micrometer + Prometheus + Grafana
- Rate limiting con Bucket4j y documentación OpenAPI/Swagger

---

### [Veterinaria App — API Reactiva en Producción](https://github.com/devbryan02/veterinaria-app-backend)
> API REST reactiva para control sanitario de mascotas de la Municipalidad A.A. Cáceres Dorregaray, Ayacucho.

**Stack:** Java 17 · Spring WebFlux · R2DBC · PostgreSQL · JWT · AOP · Apache POI · Flyway · Docker · Railway

- Arquitectura Hexagonal + CQRS con flujo `HTTP → Controller → Service → Port → Adapter → DB`
- Auditoría automática con AOP para todas las operaciones CRUD
- Exportación de reportes sanitarios a Excel con Apache POI
- **Desplegado en producción** vía Docker + Railway

---

### [Generador de Horarios Académicos](https://github.com/devbryan02/asignacion-de-horario)
> Sistema de asignación inteligente de horarios usando OptaPlanner con restricciones duras y blandas.

**Stack:** Java 17 · Spring Boot 3 · OptaPlanner 9.44 · Spring Data JPA · SQL Server · Clean Architecture

- Restricciones duras: sin choques de aula/docente, compatibilidad aula-curso, disponibilidad
- Restricciones blandas: balance de carga docente y optimización de recursos
- Solver configurado con límite de 30s, heurística inicial y búsqueda local
- Endpoints para generar horarios, consultar por período y analizar Hard/Soft score

---

### [Machine Learning — Análisis de Ventas](https://github.com/devbryan02/machine-learing-python)
> Pipeline completo de Data Science: desde limpieza de datos hasta modelo predictivo de entregas.

**Stack:** Python · Pandas · NumPy · scikit-learn · SQLAlchemy · SQLite · Matplotlib · Seaborn · joblib

- ETL completo: imputación de nulos, persistencia en SQLite con SQLAlchemy ORM
- EDA con visualizaciones: distribución, top vendedores, ventas por canal y temporalidad
- `RandomForestClassifier` con 72.9% accuracy para predecir entregas vs cancelaciones
- Feature engineering, Label Encoding y exportación del modelo entrenado con joblib

---

### [Pipeline E-commerce con OOP](https://github.com/devbryan02/pandas-y-numpy-en-python)
> Pipeline de análisis de datos con arquitectura orientada a objetos y principio SRP.

**Stack:** Python · Pandas · NumPy · Power BI · OOP · SRP

- Servicios especializados: carga, tendencias MoM, KPIs por categoría y exportación
- Resultados exportados en `.csv` y `.xlsx` optimizados para Power BI

---

## Stack principal

```
Backend        │ Java 21/17 · Spring Boot · Spring WebFlux · Spring Security
Arquitectura   │ Hexagonal · Clean Architecture · CQRS · SOLID
Base de datos  │ PostgreSQL · R2DBC · JPA/Hibernate · Flyway · SQLite
Seguridad      │ JWT · RBAC · Stateless Auth
DevOps         │ Docker · Docker Compose · Railway · Gradle · Maven
Observabilidad │ Actuator · Micrometer · Prometheus · Grafana
Testing        │ JUnit 5 · Mockito
Data           │ Python · Pandas · NumPy · scikit-learn · Power BI
```

---

## Sobre mí

- 🎓 Estudiante de último ciclo de Ingeniería de Sistemas — La Pontificia, Ayacucho
- 🏛️ Practicante en la Municipalidad Provincial de Huamanga
- 🌎 Buscando mi primer rol formal como **Junior Backend Developer** — remoto o presencial
- 📬 Abierto a oportunidades en Perú e internacionales

---

<div align="start">

```java
@Slf4j
public class DeveloperStatus {
    public static void main(String[] args) {
        log.info("Open to work | Building scalable Java APIs | Active on GitHub");
    }
}
```

*Si tu equipo necesita un backend developer que entiende arquitectura, seguridad y despliegue — hablemos.*

</div>
