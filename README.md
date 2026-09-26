# DebtLens

### AI-Powered Technical Debt Analytics Dashboard
#### For Agile Small-Scale Software Teams

> DebtLens is a full-stack SaaS platform that helps small software
> development teams identify, analyze, and prioritize technical debt
> using software metrics and machine learning.

---

## 🚀 About the Project

Technical debt is one of the major challenges faced by small software
teams working under tight deadlines. Quick fixes and shortcuts can
accumulate hidden maintenance costs and increase the risk of future
defects.

DebtLens provides a centralized platform for analyzing repository
health, visualizing technical debt, and identifying code that may
require refactoring.

---

## 🎯 Key Features

- 📊 Technical Debt Analytics Dashboard
- 🔍 Repository Health Analysis
- 🤖 Machine Learning-based Bug Prediction
- 🧠 Self-Admitted Technical Debt (SATD) Detection
- 🔥 Technical Debt Hotspot Visualization
- 📈 Code Health Trends
- ⭐ Refactor-First Prioritization
- 🔗 GitHub/GitLab Repository Integration

---

## 🏗️ System Architecture

DebtLens consists of several services:

| Component | Technology | Responsibility |
|---|---|---|
| Frontend | TypeScript | Dashboard and visualization |
| Application Service | Spring Boot | Core backend and API |
| Analysis Service | Spring Boot | Repository/code analysis |
| ML Service | Python / FastAPI | ML predictions |
| Worker | ... | Asynchronous processing |
| Database | PostgreSQL / Neon | Persistent data |
| Message Broker | RabbitMQ | Asynchronous communication |

---

## 📂 Repositories

### Frontend
User interface and technical debt dashboard.

### Application Service
Main backend application and business logic.

### Analysis Service
Repository and code analysis functionality.

### ML Service
Machine learning models for technical debt and
bug-proneness prediction.

### Deployment
Containerization and deployment configuration.

---

## 🤖 Machine Learning

The ML component focuses on:

- Self-Admitted Technical Debt classification
- Bug-proneness prediction
- Code and repository metrics
- Technical debt categorization

---

## 🔄 Project Workflow

```text
GitHub / GitLab Repository
          ↓
   Repository Analysis
          ↓
   Code & Commit Metrics
          ↓
      ML Analysis
          ↓
   Technical Debt Score
          ↓
   Dashboard & Hotspots
          ↓
   Refactor-First List
