# Task Manager App 📝

A fullstack Task Manager Web-App built as a **DevOps showcase project**.  
The goal is to demonstrate skills in **Frontend, Backend, Database, Security, Containerization, CI/CD, Cloud, Automation, and AI-light features**.  

> 🚧 Work in Progress – building step by step (Frontend → Backend → Docker → CI/CD → AWS → Automation → AI).

---

## 🚀 Tech Stack

**Frontend**
- React + TypeScript
- SCSS (Sass for styling)
- react-router-dom

**Backend**
- Node.js + Express
- PostgreSQL (via `pg`)
- JWT + bcrypt for authentication
- Helmet + CORS for security

**Infrastructure / DevOps**
- Docker + docker-compose
- GitHub Actions (CI/CD)
- AWS (EC2, RDS, S3)
- MinIO (local file storage)
- n8n (automation workflows)
- Auto-tagging (AI-light)

---

## 📂 Project Structure

```plaintext
task-manager-app/
├── frontend/      # React frontend
├── backend/       # Express backend
├── db/            # Database migrations & seeds
├── infra/         # Deployment & CI/CD
├── automation/    # n8n workflows
└── docs/          # Documentation
