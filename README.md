<details>
<summary><b>🌐 English Version</b> <i>(Click to expand)</i></summary>

<br />

# Hi there, I'm Yonghyun Cho 👋

I'm a **Computer Science** student focused on **infrastructure, cloud architecture, computer networking, and containerized service operations**.  
From self-hosted home servers to AWS Terraform IaC, automated CI/CD pipelines, and Spring Boot backends, I enjoy building and operating the complete path from code to production.

---

## 👨‍💻 About Me

- 🎓 Currently studying **Computer Science**, focusing on **cloud architecture**, **networking**, and **systems infrastructure**.
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

</details>

# 안녕하세요, 조용현(Yonghyun Cho)입니다 👋

**인프라·클라우드·네트워크와 컨테이너 기반 서비스 운영**에 깊은 관심을 가진 컴퓨터공학 전공 대학생입니다.  
개인 홈서버 운영부터 AWS Terraform IaC, CI/CD 자동화, 백엔드 API 개발까지 **서비스가 안정적으로 설계되고 배포·운영되는 전체 흐름**을 직접 구축하는 것을 즐깁니다.

---

## 👨‍💻 About Me

- 🎓 **Computer Science**를 전공하며 **클라우드 아키텍처**, **네트워크**, **시스템 인프라**를 깊이 공부하고 있습니다.
- 🖥️ **Home Lab & Self-Hosting**: Ubuntu · Docker · Tailscale 기반 개인 홈서버를 직접 구축·운영하며 컨테이너화된 서비스를 관리합니다.
- ☁️ **Infrastructure & DevOps**: Terraform(AWS) IaC, GitHub Actions(Self-hosted Runner), Jenkins 파이프라인 등 반복 가능한 배포 인프라 구축 경험을 보유하고 있습니다.
- ⚙️ **Backend & Full-Stack**: 인프라를 이해하는 개발자로서 Java/Spring Boot 기반 백엔드 및 Next.js/React 연동·트러블슈팅까지 함께 수행합니다.

---

## 🚀 Featured Projects

> ℹ️ 아래 모든 프로젝트는 **현재 라이브 서비스 배포가 종료되어 외부 접속이 불가능**합니다. 전체 소스코드와 인프라 설정은 각 GitHub 저장소에서 확인하실 수 있습니다.

### 1. MixChat — 실시간 AI 번역 채팅 & 커뮤니티
> **2025.11 – 2025.12** · Programmers AI·BE DevCourse Final Project · *(배포 종료)*  
> 🔗 [Backend Repo](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_BE) · [Frontend Repo](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_FE) · [Terraform 인프라 문서](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_BE/blob/main/docs/terraform.md) · [Terraform 코드](https://github.com/prgrms-aibe-devcourse/AIBE3_final_project_team3_BE/blob/main/infra/main.tf)

- **AWS Terraform IaC 설계 및 구축**: VPC(`10.0.0.0/16`), Public/Private 서브넷, IGW·라우트 테이블, Security Group, IAM/SSM, EC2(Amazon Linux 2023 + `base64gzip` user-data 부트스트랩), RDS(MySQL 8.0), S3(Prod/Staging 분리)를 코드로 정의하고 운영 문서를 작성했습니다.
- **CI/CD 및 배포 환경 분리**: GitHub Actions(Self-hosted Runner, GHCR)와 Docker Compose 기반 자동 빌드·배포 파이프라인, Nginx Proxy Manager 리버스 프록시, `dev`/`release`/`main` 브랜치 릴리즈 관리를 담당했습니다.
- **커뮤니티 게시판 도메인 풀스택 개발**: 게시글·댓글·좋아요·S3 이미지 업로드 백엔드(Spring Boot 3 / JPA) 및 Next.js 게시판 UI 연동, 배포 시 CORS·빌드 이슈 해결을 수행했습니다.

**Stack:** `Terraform` `AWS (EC2, RDS, S3, VPC, IAM)` `Docker Compose` `GitHub Actions` `Nginx Proxy Manager` `Java 21` `Spring Boot` `MySQL` `Redis` `Next.js`

---

### 2. WorkBuddy — 프리랜서·클라이언트 매칭 플랫폼
> **2025.10** · Programmers AI·BE DevCourse Team Project (팀 내 최다 커밋 기여) · *(배포 종료)*  
> 🔗 [Repository](https://github.com/prgrms-aibe-devcourse/AIBE3-TEAM2-BeanBuddies-MatchingPlatform) · [Jenkinsfile](https://github.com/prgrms-aibe-devcourse/AIBE3-TEAM2-BeanBuddies-MatchingPlatform/blob/main/Jenkinsfile)

- **Jenkins + Docker CI/CD 자동화 (배포 시간 80% 단축)**: Backend(Spring Boot)와 Frontend(React/Vite)의 빌드, Docker Hub 이미지 푸시, SSH 기반 원격 컨테이너 배포 파이프라인을 처음부터 구축했습니다.
- **자체 서버 실서비스 호스팅**: 개인 홈서버 인프라와 커스텀 도메인 환경에 팀 서비스를 직접 배포·운영하며, OAuth2(Kakao·Naver·Google) 소셜 로그인·Spring Security·CORS·Redis·SMTP 배포 환경 문제를 해결했습니다.
- **마이페이지 풀스택 개발**: 프로필 조회·수정·공개 범위 설정, 기술스택/경력 관리, 관심 프로젝트·프리랜서 즐겨찾기, 등록/지원 프로젝트 관리 API 및 프론트엔드 연동을 구현했습니다.

**Stack:** `Jenkins` `Docker` `Ubuntu` `Reverse Proxy` `Java 21` `Spring Boot` `Spring Security` `MySQL` `Redis` `React` `TypeScript` `Vite`

---

### 3. AI Travel Planner — 여행 계획 추천 플랫폼
> **2025.07** · Programmers AI·BE DevCourse 1st Project · *(배포 종료)*  
> 🔗 [Repository](https://github.com/prgrms-aibe-devcourse/AIBE3-Project1-Team03)

- **배포 및 보안·네트워크 트러블슈팅**: Vercel 프로덕션 배포를 총괄하고, 외부 공공데이터 API 프록시 라우트 구성·CORS 헤더 처리·프로덕션 빌드 오류 해결 및 Supabase RLS(Row Level Security) 정책·에러 핸들링을 적용했습니다.
- **마이페이지 여행 플래너 구현**: 여행 일정 및 세부 계획 CRUD 기능을 개발하고, 팀 PR 리뷰·병합 과정에 적극 참여했습니다.

**Stack:** `Next.js` `TypeScript` `Supabase (PostgreSQL, RLS)` `Tailwind CSS` `Vercel`

---

## 🖥️ Home Lab & Self-Hosting

- **Operating Environment**: Ubuntu Linux 서버 위에서 Docker / Docker Compose 기반으로 개인 서비스와 모니터링 대시보드를 컨테이너화해 내부 환경에서 상시 운영합니다.
- **Private Networking**: Tailscale 메시 VPN과 리버스 프록시(Nginx Proxy Manager)를 활용해 외부 노출을 최소화하면서 안전하게 내부 서비스와 원격 개발 환경에 접근합니다.
- **CI/CD Runner & Hosting**: GitHub Actions Self-hosted Runner, Jenkins, 팀 프로젝트 프로덕션/스테이징 호스팅까지 직접 실험하고 운영하며 실전 인프라 감각을 키우고 있습니다.

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
