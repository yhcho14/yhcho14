<div align="right">
  <a href="https://github.com/yhcho14"><img src="https://img.shields.io/badge/한국어-Switch-2563EB?style=flat-square" alt="한국어" /></a>
  <a href="https://github.com/yhcho14/yhcho14/blob/main/README.en.md"><img src="https://img.shields.io/badge/Language-English-1F2937?style=flat-square" alt="English" /></a>
</div>

# Hi there, I'm Yonghyun Cho 👋

I'm a **Computer Science** student focused on **infrastructure, cloud architecture, computer networking, and containerized service operations**.  
From self-hosted home servers to AWS Terraform IaC, automated CI/CD pipelines, and Spring Boot backends, I enjoy building and operating the complete path from code to production.

---

## 👨‍💻 About Me

- 🎓 Currently studying **Computer Science**, deepening my knowledge in **Computer Networking** and **Machine Learning**.
- 🖥️ **Home Lab & Self-Hosting**: Passionate about building Ubuntu/Docker home servers, managing private mesh networks with Tailscale, and operating self-hosted containerized services.
- ☁️ **Infrastructure & DevOps**: Hands-on experience designing AWS infrastructure with Terraform, building CI/CD workflows (GitHub Actions, Self-hosted Runners, Jenkins), and automating containerized deployments.
- ⚙️ **Backend & Full-Stack**: Experienced in delivering Spring Boot APIs and TypeScript/Next.js integrations alongside production deployment and troubleshooting.

---

## 🚀 Featured Projects

> ℹ️ Live deployments for all projects below are currently **offline (decommissioned after project completion)** and no longer publicly accessible. Full source code and infrastructure configurations are available in the linked GitHub repositories.

### 1. MixChat — Real-Time AI Translation Chat & Community
> **2025.11 – 2025.12** · Programmers AI·BE DevCourse Final Project · *(Live service offline)*  
> 🔗 [Backend Repo](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_BE) · [Frontend Repo](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_FE) · [Terraform Guide](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_BE/blob/main/docs/terraform.md) · [Terraform IaC](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_BE/blob/main/infra/main.tf)

- **AWS Infrastructure as Code (Terraform)**: Provisioned VPC (`10.0.0.0/16`), public/private subnets, Internet Gateway, route tables, security groups, IAM/SSM roles, Amazon Linux 2023 EC2 instances bootstrapped via `base64gzip` user-data, MySQL 8.0 RDS, and separated Prod/Staging S3 buckets.
- **CI/CD & Environment Operations**: Built GitHub Actions CI/CD pipelines (GHCR, Self-hosted Runner, Docker Compose auto-deploy), configured Nginx Proxy Manager reverse proxy, and managed `dev` / `release` / `main` release workflows.
- **Full-Stack Community Domain**: Implemented the Post/Comment/Like/S3-image backend (Spring Boot 3 / JPA) and Next.js board frontend, resolving production CORS and build issues.

**Stack:** `Terraform` `AWS (EC2, RDS, S3, VPC, IAM)` `Docker Compose` `GitHub Actions` `Nginx Proxy Manager` `Java 21` `Spring Boot` `MySQL` `Redis` `Next.js`

---

### 2. WorkBuddy — Freelancer & Client Matching Platform
> **2025.10** · Programmers AI·BE DevCourse Team Project (Top Committer) · *(Live service offline)*  
> 🔗 [Repository](https://github.com/prgrms-aibe-devcourse/AIBE3-TEAM2-BeanBuddies-MatchingPlatform) · [Jenkinsfile](https://github.com/prgrms-aibe-devcourse/AIBE3-TEAM2-BeanBuddies-MatchingPlatform/blob/main/Jenkinsfile)

- **End-to-End Jenkins & Docker CI/CD (80% faster deployment)**: Built automated build, Docker Hub push, and SSH container deployment pipelines for both Backend (Spring Boot) and Frontend (React/Vite).
- **Self-Hosted Production Operations**: Hosted the team's live service and API on personal home-server infrastructure with a custom domain, resolving production OAuth2 (Kakao/Naver/Google), Spring Security, CORS, Redis, and SMTP issues.
- **Full-Stack MyPage & Favorites**: Built profile management, visibility scopes, skill/career editing, project/freelancer favorites, and application tracking APIs with frontend integration.

**Stack:** `Jenkins` `Docker` `Ubuntu` `Reverse Proxy` `Java 21` `Spring Boot` `Spring Security` `MySQL` `Redis` `React` `TypeScript` `Vite`

---

### 3. AI Travel Planner — Travel Recommendation & Itinerary Platform
> **2025.07** · Programmers AI·BE DevCourse 1st Project · *(Live service offline)*  
> 🔗 [Repository](https://github.com/prgrms-aibe-devcourse/AIBE3-Project1-Team03)

- **Deployment, Security & API Proxy**: Owned Vercel production deployment, implemented external public-data API proxy routes with CORS handling, resolved production build issues, and configured Supabase Row Level Security (RLS) error handling.
- **MyPage Travel Planner**: Built travel plan & detailed itinerary CRUD workflows and actively reviewed/merged team PRs.

**Stack:** `Next.js` `TypeScript` `Supabase (PostgreSQL, RLS)` `Tailwind CSS` `Vercel`

---

## 🖥️ Home Lab & Self-Hosting

- **Containerized Services**: Operate personal Ubuntu Linux home server workloads with Docker / Docker Compose, running self-hosted services and monitoring dashboards in a private environment.
- **Zero-Trust Private Networking**: Use Tailscale mesh VPN and reverse proxy (Nginx Proxy Manager) for secure remote administration and minimal public attack surface.
- **Hands-On DevOps Sandbox**: Run self-hosted GitHub Actions runners, Jenkins agents, and staging/production environments for real-world team projects.

---

## 🛠️ Tech Stack

### Infrastructure, Cloud & Networking
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white)

### Containers & CI/CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

### Backend, Data & Web
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

---

## 📫 Contact

[![Email](https://img.shields.io/badge/Email-yonghyun.cho@outlook.com-0078D4?style=for-the-badge)](mailto:yonghyun.cho@outlook.com)