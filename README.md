<div align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&multiline=false&repeat=true&width=700&height=60&lines=Hi%2C+I'm+Lucas+Martinez+%F0%9F%91%8B;DevOps+Engineer;Docker+%7C+Kubernetes+%7C+Terraform;AWS+Certified+Solutions+Architect;Open+to+Remote+DevOps+%26+SRE+Roles"
    alt="Typing SVG"
  />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=LucasMartinez99&color=3B82F6&style=flat" alt="Profile Views" />
  <a href="mailto:lucasmartinez.090599@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/lucas-software-engineer/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Asunci%C3%B3n%2C+PY+(GMT--3)-3B82F6?style=flat" />
  <img src="https://img.shields.io/badge/Open%20to%20Work-Yes-22c55e?style=flat" />
</div>

---

## About Me

DevOps Engineer focused on **infrastructure automation, observability, and CI/CD**. I run production systems end-to-end — from containerized deployments to monitoring stacks and automated backups. My background in backend development means I understand the applications I deploy, not just the pipelines around them.

- 🏗 Operating a **self-managed Linux VPS** in production: Docker Compose stacks, Nginx reverse proxy, TLS automation, resource isolation and hardening
- 🔭 Built a full **observability stack** from scratch: Prometheus + Grafana + cAdvisor + node_exporter, with 5 tuned alert rules routed to Discord
- ⚙️ Automated CI/CD pipelines with **GitHub Actions**: push to main → SSH → rebuild changed container → health check → done
- ☁️ **AWS Certified Solutions Architect Associate** — hands-on with EC2, S3, CloudFront, VPC, RDS, IAM
- 🐧 Studying for **Red Hat RHCSA** — going deep on Linux internals, not just surface-level usage
- 💾 S3 backup automation with tested restores — because backups aren't real until you've restored from them

---

## 🏗 Featured Infrastructure Project

### homelab-infra — Production Self-Hosted Infrastructure
> [GitHub](https://github.com/LucasMartinez99/homelab-infra)

A case study of the production infrastructure I operate on a single Linux VPS. Not a tutorial — real systems, real problems, real lessons.

**Architecture**
- Cloudflare (DNS, WAF, DDoS) → Nginx reverse proxy (TLS termination) → Docker Compose app stacks
- Full network isolation: internal services never exposed on host ports, only Nginx on the public network
- Memory limits on every critical container — a runaway process can't take down the host

**Observability**
- Prometheus + Grafana + cAdvisor + node_exporter
- 5 alert rules (container down, RAM > 90%, disk > 85%, CPU > 85%, container hogging a core)
- Each alert has a pending period to filter transient spikes — alert fatigue is a real failure mode

**Operations**
- Certbot auto-renews TLS and reloads Nginx with zero downtime
- Daily cron job dumps Postgres + MySQL → encrypted upload to versioned S3 bucket
- GitHub Actions CI/CD: SSH deploy, rebuild only the changed container, health check

**Cost:** ~$18/month for a full production stack. Equivalent AWS-managed setup would run $200-400/month.

---

## 🚀 Application Project (CI/CD showcase)

### URL Shortener — Full Stack, Production Deployed
> Live at **[urls.syspar.com.py](https://urls.syspar.com.py)**

Built to showcase real deployment practices, not just application code.

- Containerized with Docker Compose (backend + frontend + Nginx)
- Zero-downtime deploys via GitHub Actions — push to `main` triggers SSH, rebuild, health check
- Backend: Java 21 + Spring Boot 3, PostgreSQL, JWT auth, rate limiting, Testcontainers integration tests
- Frontend: React 19 + TypeScript, served via Nginx in Docker

The app exists to demonstrate the **full DevOps loop**: code → test → build → deploy → monitor.

---

## 🛠 Tech Stack

**Infrastructure & DevOps**
<p>
  <img src="https://skillicons.dev/icons?i=linux,docker,aws,nginx,prometheus,grafana" />
</p>

**Automation & IaC (in progress)**
<p>
  <img src="https://skillicons.dev/icons?i=terraform,kubernetes,github,bash" />
</p>

**Application layer (background, used in deployments)**
<p>
  <img src="https://skillicons.dev/icons?i=java,spring,postgresql,react,php" />
</p>

---

## 📜 Certifications

| Certification | Issuer | Year | Verify |
|---|---|---|---|
| **Solutions Architect – Associate** | AWS | 2026 | [Credly](https://www.credly.com/badges/26f2d025-f86f-4e5d-8b2f-54a1ee18e68c/public_url) |
| Scrum Foundation (SFC) | SCRUMstudy | 2025 | [Verify](https://www.scrumstudy.com/certification/verify?type=SFC&number=1073117) |
| English Certificate (B2) | EF SET | 2026 | [View](https://cert.efset.org/en/WBBWFw) |
| Linux Server Management for Developers | Udemy | 2024 | [View](https://udemy-certificate.s3.amazonaws.com/image/UC-b928de8d-836f-4bc9-9c8e-dd4ca87eb20f.jpg) |

### Certification Roadmap
```text
[✅] AWS Certified Solutions Architect – Associate
[🔄] Red Hat RHCSA                          ← In progress
[ ]  HashiCorp Terraform Associate
[ ]  CKA – Certified Kubernetes Administrator
[ ]  CompTIA Network+
```

---

## 📊 GitHub Stats

<img height="180em" src="https://streak-stats.demolab.com?user=LucasMartinez99&theme=tokyonight&hide_border=true" />

---

## 📫 Let's Connect

I'm actively looking for **remote DevOps / Infrastructure Engineer** opportunities. If you're hiring or want to talk infrastructure — reach out.

<p>
  <a href="mailto:lucasmartinez.090599@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/lucas-software-engineer/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>
