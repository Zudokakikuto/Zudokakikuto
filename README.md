# 👋 Hi, I'm **Julien Leblond**
Developer | Java & Spring Boot • Python & FastAPI • Docker • CI/CD  

---

## 🚀 What I Do

- **Build robust APIs** – micro‑service architectures with **Spring Boot** (Java 17) and **FastAPI** (Python 3.11).  
- **Continuous Integration & Delivery** – GitHub Actions pipelines, unit tests, linting, Docker image builds, and publishing to Docker Hub.  
- **Containerization & Orchestration** – Docker, Docker‑Compose, PostgreSQL, and Redis caches.  
- **Light‑weight data‑science** – scoring models (scikit‑learn) embedded in Python services for fraud detection.  
- **API Documentation** – OpenAPI/Swagger, architecture diagrams, detailed READMEs.  

---

## 🛠️ Current Toolbox

| Language | Framework / Library | Orchestration | CI / Tests |
|----------|---------------------|---------------|-----------|
| **Java 17** | Spring Boot, Spring Data JPA, Springdoc‑OpenAPI | Docker, Docker‑Compose | Maven, JUnit 5, SpotBugs, GitHub Actions |
| **Python 3.11** | FastAPI, Uvicorn, scikit‑learn, pydantic | Docker, Docker‑Compose | pytest, httpx, GitHub Actions |
| **Database** | PostgreSQL | – | Flyway migrations |
| **CI/CD** | GitHub Actions (build, test, push) | Docker Hub (image registry) | SonarCloud (optional) |
| **Containerization**| Docker/Podman | Docker, Docker‑Compose |
---

## 🌟 Flagship Project: **Pay‑Guard**

> **Secure payment API + fraud‑scoring service** – a complete demo showing how **Java** and **Python** can work together in a containerised environment, with fully automated CI/CD.

| 🎯 Goal | ⚙️ Stack | 📦 Deliverables |
|--------|----------|-----------------|
| Build a *payments* API (Spring Boot) that persists transactions. | Java 17, Spring Boot, PostgreSQL, Docker | `java-api/` + `Dockerfile` |
| Add a fraud‑scoring micro‑service (FastAPI) that returns a 0‑1 score. | Python 3.11, FastAPI, Docker | `python-fraud/` + `model.pkl` |
| Orchestrate both services + DB + cache via **Docker‑Compose**. | Docker‑Compose, PostgreSQL | `docker-compose.yml` |
| Implement **CI/CD**: tests, lint, image build, push to Docker Hub. | GitHub Actions, Maven, pytest | `.github/workflows/ci.yml` |
| Document the API (OpenAPI) and provide a **live demo** (Render / Fly.io). | Springdoc‑OpenAPI, FastAPI docs, Swagger UI | `docs/api-spec.yaml`, demo URL in the README |
