<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,100:0F172A&height=200&section=header&text=Mujahid%20Suliman&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38" />

### Junior DevSecOps Engineer • Python Backend • Cloud

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=700&size=28&duration=3000&pause=800&center=true&vCenter=true&width=850&lines=Junior+DevSecOps+Engineer;CI%2FCD+%26+Security+Scanning+Pipelines;Docker+%7C+Terraform+%7C+AWS+%7C+GitHub+Actions;Python+%7C+FastAPI+%7C+PostgreSQL;Building+in+Public+%F0%9F%9A%80" />

Building pipelines where security is a required gate, not an afterthought.

</div>

---

## 🚀 About Me

I'm a Junior DevSecOps Engineer with an MSc in Information Technology and a Python backend background. I build pipelines that treat security as a required gate: every change is linted, tested, and scanned (SAST, secret scanning, dependency and container vulnerability scanning) before an image is ever published.

My projects form one chain: a hardened Flask API in a non-root, read-only Docker image shipped through a 6-stage GitHub Actions pipeline to GHCR; Terraform that provisions AWS infrastructure and runs that same image; and **[ResumeIQ](https://resumeiq-beta-ten.vercel.app)**, a full-stack AI application (FastAPI, PostgreSQL, React) deployed on Render and Vercel with its own CI/CD, Dependabot updates, and Trivy-verified dependencies.

> Learn → Build → Share

---

## 🎯 What I'm Focused On

- 🔐 **DevSecOps**: CI/CD pipelines with SAST, secret scanning, and dependency and container scanning
- ☁️ **Infrastructure as Code**: Terraform on AWS, with IaC scanning in CI
- 🐳 Docker hardening: non-root users, read-only filesystems, runtime-only secrets
- ⚡ Backend systems with Python, FastAPI and PostgreSQL
- 📈 Observability basics: Prometheus metrics and health checks
- 📚 Building in public and sharing what I learn
- 💼 Open to Junior DevSecOps, DevOps, Cloud, and Python backend roles

---

## ⚡ Tech Stack

**Languages**
<img src="https://skillicons.dev/icons?i=python,ts,js,html,css" />

**Backend**
<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs" />

**Frontend**
<img src="https://skillicons.dev/icons?i=react,vite,tailwind" />

**Database**
<img src="https://skillicons.dev/icons?i=postgresql,mysql,sqlite" />

**Cloud & DevOps**
<img src="https://skillicons.dev/icons?i=docker,githubactions,terraform,aws,vercel,linux,git,github,nginx" />

**Security tooling**
Bandit (SAST) · Gitleaks (secret scanning) · Trivy (dependency, image and IaC scanning) · Dependabot

**AI / LLM**
OpenRouter · OpenAI-compatible APIs · Prompt Engineering · LLM Applications

---

## 🏆 Projects

Three projects that connect into one chain: code → CI/CD with security gates → container image → infrastructure as code → running service.

### 1. [DevSecOps CI/CD Pipeline](https://github.com/M-249S/devops-cicd-project)

A Flask API in a hardened Docker image, shipped through a 6-stage GitHub Actions pipeline that refuses to publish anything that fails a security check.

- Pipeline: flake8, pytest, Bandit (SAST), Gitleaks (secrets), Trivy (dependencies and image), then publish to GHCR only if everything passes
- Container runs as non-root with a read-only filesystem; secrets are injected at runtime only
- Prometheus metrics (`/metrics`) following the RED method

**Stack:** Python · Flask · Gunicorn · Docker · GitHub Actions · Trivy · Bandit · Gitleaks · Prometheus

### 2. [Terraform AWS EC2 Demo](https://github.com/M-249S/terraform-ec2-demo)

Terraform provisions an AWS EC2 instance and security group, and boots it running the image published by project 1.

- AMI looked up dynamically, boot script installs Docker and runs the container with the same hardening
- CI runs `terraform fmt`, `validate` and a Trivy IaC scan, with no AWS credentials needed

**Stack:** Terraform · AWS EC2 · Docker · GitHub Actions · Trivy

### 3. [ResumeIQ](https://github.com/M-249S/resumeiq): AI Resume Analyzer

Full-stack app that scores resumes against a job description, rewrites them, and generates tailored cover letters, with saved history per user.
**[Live demo](https://resumeiq-beta-ten.vercel.app)**

- JWT authentication, PostgreSQL with Alembic migrations, rate-limited AI endpoints with retries and fallback models
- Own 6-stage CI/CD pipeline, Dependabot grouped updates, and real CVEs found by Trivy and fixed
- Dockerized backend on Render (Blueprint), frontend on Vercel

**Stack:** FastAPI · PostgreSQL · React · TypeScript · Docker · GitHub Actions

---

## 💼 Available For

| Service | Status |
|---|---|
| CI/CD & Security Scanning Pipelines | ✅ Available |
| Docker & Infrastructure as Code (Terraform) | ✅ Available |
| Backend Development (FastAPI) | ✅ Available |
| Python Automation | ✅ Available |

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=M-249S&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=1800"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=M-249S&layout=compact&theme=tokyonight&hide_border=true&cache_seconds=1800"/>

<img src="https://streak-stats.demolab.com?user=M-249S&theme=tokyonight&hide_border=true"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=M-249S&theme=tokyo-night&hide_border=true"/>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/M-249S/M-249S/output/github-contribution-grid-snake.svg" />

</div>

> Updates automatically via the `snake.yml` GitHub Action on every contribution.

---

## 🌍 Connect With Me

<p align="center">
<a href="https://www.linkedin.com/in/mujahid-suliman-6a9875425/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://x.com/MujahidCode"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
<a href="https://github.com/M-249S"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.reddit.com/user/Remote_Singer_6287/"><img src="https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white"/></a>
<a href="https://resumeiq-beta-ten.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-ResumeIQ-0A66C2?style=for-the-badge"/></a>
</p>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=M-249S&label=Profile%20Views&color=0A66C2&style=for-the-badge"/>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:2563EB&height=150&section=footer&animation=fadeIn" />

<div align="center">

**Building secure pipelines in public.**
Learn → Build → Share

</div>
