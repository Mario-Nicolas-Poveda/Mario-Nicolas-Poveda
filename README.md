# Hola, soy Mario Poveda 👋

Estudiante de **Ingeniería de Sistemas** en la Universidad Popular del Cesar (Valledupar, Colombia).
Me interesan el **desarrollo backend** y la **ingeniería de datos**: APIs, bases de datos y pipelines que convierten datos en decisiones.

---

## 📌 Proyectos destacados

### ♟️ [Chess Predictor Pro](https://github.com/Mario-Nicolas-Poveda/chess-predictor-pro) · [Demo en vivo](https://chess-predictor-pro.vercel.app)
Ajedrez en línea con ELO, partidas en tiempo real, IA de 6 niveles con predicción de la probabilidad de ganar, AI Coach que analiza tus partidas, ranking global y torneos de eliminación directa.
- **Mi rol:** backend (API REST, base de datos, autenticación con JWT y Google OAuth, CI y releases).
- **Stack:** Next.js · TypeScript · Supabase (PostgreSQL + Realtime) · Zod · Vitest · GitHub Actions · Vercel
- Arquitectura limpia por módulos; las operaciones críticas (jugadas, reloj, ELO, avance de torneos) son funciones SQL atómicas.

### 🚕 [Pipeline BI — NYC Yellow Taxi](https://github.com/Mario-Nicolas-Poveda/pipeline-taxi-bi)
Pipeline de datos de punta a punta con **arquitectura Medallion** (Bronze / Silver / Gold) sobre **187 M de viajes reales** de taxis de Nueva York (2018-2019, un recorte del dataset público de más de 1.000 M).
- **Mi rol:** modelos dbt de las capas Silver y Gold, pruebas de calidad de datos y el repositorio.
- **Stack:** Python · PySpark · Databricks · Delta Lake · Kafka (Confluent Cloud) · dbt · BigQuery · Power BI
- Esquema estrella con una tabla de hechos de 175 M de filas, 6/6 pruebas de calidad aprobadas, Kafka para simular la llegada de datos en tiempo real y 3 dashboards en Power BI.

### 🔊 [AcústicaUPC](https://github.com/JoseJulioGP/ProyectoAcusticaUPC) · [Demo en vivo](https://proyecto-acustica-upc.vercel.app)
Sistema de BI para monitorear el ruido en la universidad: ingiere mediciones de sonómetro (Excel), evalúa el cumplimiento de la **Resolución 0627 de 2006** y muestra KPIs, mapa de calor, alertas y reportes PDF.
- **Mi aporte:** backend (analítica y KPIs, ingesta asíncrona de archivos, seguridad y roles, pruebas con Testcontainers y despliegue en Render).
- **Stack:** Java · Spring Boot · Spring Security (JWT) · PostgreSQL (Supabase) · Flyway · Apache POI · React · Docker

---

## 🛠️ Tecnologías

**Lenguajes:** Java · TypeScript · JavaScript · Python · SQL
**Backend:** Spring Boot · Next.js · APIs REST · JWT / OAuth 2.0
**Datos:** PostgreSQL · MongoDB · PySpark · Databricks · dbt · Kafka · BigQuery · Power BI
**Herramientas:** Git / GitHub · GitHub Actions · Docker · Supabase · Vercel · Render
