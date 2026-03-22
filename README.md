# 📊 Airflow + dbt + PostgreSQL Project

Modern ELT pipeline that loads data into PostgreSQL, transforms it with dbt, and orchestrates everything via Apache Airflow — fully containerized with Docker.

---

## 🎯 Objective

Implement an automated ELT pipeline following a layered approach (staging → marts), with a clear separation between orchestration (Airflow) and transformation (dbt), applying data engineering best practices.

---

## 🛠️ Technologies

| Technology | Use |
|---|---|
| Python | Main language |
| Apache Airflow | Pipeline orchestration |
| dbt | Data transformation and modeling |
| PostgreSQL | Data warehouse |
| Docker / Docker Compose | Containerized infrastructure |

---

## 🗂️ Structure

```
airflow-dbt-postgres-project/
└── weather-data-project/
    ├── dags/               # Airflow DAGs
    ├── dbt/
    │   ├── models/
    │   │   ├── staging/    # Staging models
    │   │   └── marts/      # Final models
    │   └── profiles.yml
    └── docker-compose.yaml
```

---
