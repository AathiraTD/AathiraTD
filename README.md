# 🚀 Featured Projects

---

### [Goal-Tracker](https://github.com/AathiraTD/Goal-Tracker)
**A full-stack, open-source daily goal & habit tracker built with Next.js and Supabase.**

**Technical Highlights:**  
- **Frontend:** Next.js 15 App Router, React 19, Tailwind CSS 4  
- **Backend & DB:** Supabase (auth, Postgres), tRPC for type-safe API, Zod validation  
- **Tooling:** Turborepo, pnpm, Storybook 8, Playwright, Vitest  
- **Features:** Real-time goal management, analytics dashboards, authentication, responsive and accessible UI

**Learnings:**  
- Built a scalable, modern React app with advanced routing and SSR.
- Integrated end-to-end type safety and validation across the stack.
- Implemented modular UI with Storybook and robust e2e testing via Playwright.
- Gained experience with cloud Postgres, CI/CD, and monorepo tooling.

---

### [realtime-market-data-pipeline](https://github.com/AathiraTD/realtime-market-data-pipeline)
**Sub-hour insight for FTSE equities & FX rates – real-time data pipeline with Airflow, Snowflake, and Superset.**

**Technical Highlights:**  
- **Orchestration:** Apache Airflow (DAGs for data ingestion, transformation, alerting)  
- **Data Warehouse:** Snowflake (fast transformation, auto-suspend for cost savings)  
- **Visualization:** Apache Superset (automatic dashboard updates)  
- **Alerting:** Slack webhooks for job/data failures  
- **Containerization:** Docker & Docker Compose for local development and deployment

**Learnings:**  
- Built a robust, modular data pipeline ingesting and transforming 100k+ rows daily.
- Optimized for low-latency, low-cost operation via auto-scaling and efficient scheduling.
- Automated data QC and incident notification, reducing stale-data risk.
- Designed for extensibility (new markets, cloud deployment, cost analytics) and reproducibility (pre-commit hooks, infra-as-code).

---

### [SignGenie](https://github.com/AathiraTD/SignGenie)
**Real-time sign language recognition using deep learning and MLOps.**

**Technical Highlights:**  
- **Detection & Vision:** YOLO-based hand/gesture detector, OpenCV for preprocessing  
- **Sequence Modeling:** LSTM/Transformer for sign language sequence classification  
- **API:** FastAPI microservice exposes inference & health endpoints  
- **Experiment Tracking:** MLflow for reproducibility (params, metrics, artifacts)  
- **Deployment:** Docker containerization, AWS ECS for scalable cloud inference  
- **CI/CD:** GitHub Actions for automated testing, build, and deployment

**Learnings:**  
- Delivered sub-300ms inference for natural, real-time sign translation.
- Built a modular, production-grade ML pipeline (from training to serving).
- Automated experiment tracking, model registry, and versioned deployments.
- Explored cloud-native, containerized MLops and practical API-first design.

---

_See each repo for architecture diagrams, setup instructions, and code!_
