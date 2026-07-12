<h1 align="center">Hi, I'm Xavier 👋</h1>
<h3 align="center">Senior Platform Engineer / SRE — turning infrastructure into code</h3>

<p align="center">
  I build and operate cloud platforms for high-traffic systems: infrastructure as code,
  GitOps delivery, and reliability at scale. I automate the path from commit to production
  and keep critical systems reliable, secure and cost-efficient — from architecting
  platforms out of nothing to driving multi-year migrations to completion.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Senior%20Platform%20Engineer-%2F%20SRE-2496ED?style=flat-square" alt="Role" />
  <img src="https://img.shields.io/badge/Reliability-at%20scale-success?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Based%20in-Barcelona%20%F0%9F%87%AA%F0%9F%87%B8-orange?style=flat-square" alt="Location" />
</p>

---

### 🛠️ What I do

- **Infrastructure as Code** — everything versioned and reproducible; declarative over imperative (Terraform / Terragrunt), remote state with locking, domain-scoped modules with independent CI and semantic-versioned releases.
- **GitOps & CD** — build reusable delivery platforms on Argo CD (Terraform module + Helm chart, CRD-level RBAC, command-based deploy with rollback) across multiple environments.
- **Reliability at scale** — SLO-driven alerting and error budgets, runbooks, blameless postmortems; debugging large-scale sync and connector failures deep in the codebase.
- **Security & compliance** — secrets on HashiCorp Vault (+ VSO), WAF with managed rules, private CDN origins, Falco runtime security, and SOC2 audit evidence.
- **Cost & platform efficiency** — re-architecting ingestion and CI to cut spend by six figures a year while increasing capacity.

---

### 🚩 Selected work

- **Org-wide GitOps platform across three generations** — designed, migrated and decommissioned each: Atlantis → an in-house successor → **Argo CD**, owning the full lifecycle. Rolled out across 5 environments with Vault-sourced credentials, an ECR OCI token rotator, RBAC and rollback.
- **Data-ingestion migration (Fivetran → Airbyte)** — designed and deployed a production ingestion platform on Kubernetes / Terraform / Helm handling **2 TB+ datasets**, cutting cost by **~$200K/year**.
- **Security & compliance hardening** — Vault + VSO secrets across all services, reusable WAF module, CloudFront public→private origin migration, Falco runtime security, and **SOC2 Type 1** evidence.
- **Self-service Internal Developer Platform (Next.js)** — a portal letting the data team provision/tear down database replicas via automatically generated infrastructure PRs, with Slack + Datadog integration — removing SRE from the loop.
- **CI/CD scaling** — migrated all GitHub Actions workflows from EC2 to Kubernetes runners on a purpose-built EKS cluster, scaling capacity for large parallel workloads.

---

### 🧰 Tech & tooling

**Cloud & containers**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**IaC & GitOps / CI/CD**
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat-square&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/Terragrunt-2AA1FF?style=flat-square)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Renovate](https://img.shields.io/badge/Renovate-1A1F6C?style=flat-square&logo=renovatebot&logoColor=white)

**Security & observability**
![Vault](https://img.shields.io/badge/Vault-000000?style=flat-square&logo=vault&logoColor=white)
![Falco](https://img.shields.io/badge/Falco-00AEC7?style=flat-square&logo=falco&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Data & stores**
![Airbyte](https://img.shields.io/badge/Airbyte-615EFF?style=flat-square&logo=airbyte&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

### 🧪 Ventures & products

I also build and operate products end to end — so I stay close to what I automate:

- **[Smashbase](https://smashbase.io)** — a SaaS I build end to end: a tournament & league management platform for padel clubs (registrations, groups, brackets, AI-optimized scheduling, live results). A real multi-service architecture — API, payments, background workers, and admin + public frontends with async messaging.
- **[Femutech](https://femutech.com)** — my AWS cloud-optimization consultancy: cutting cloud bills up to 50% through infrastructure optimization, scalability and monitoring.

---

### 📈 Currently

- Driving GitOps delivery with Argo CD and sharpening SLO-based alerting and error-budget practice.
- Bringing production-grade IaC, security and observability patterns into my public work.

---

### 📫 Get in touch

<p align="left">
  <a href="mailto:info@xurtasun.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/xurtasun"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<sub><i>Declarative over imperative. Least privilege by default. Automate the toil, alert on the symptom.</i></sub>
