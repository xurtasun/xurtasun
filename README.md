<h1 align="center">Hi, I'm Xavier 👋</h1>
<h3 align="center">Senior Platform Engineer / SRE, based in Barcelona</h3>

<p align="center">
  I build the platforms other engineers ship on, and I keep them running. Most of my work
  lives in that space between "it works on my machine" and a system a whole org depends on:
  infrastructure as code, GitOps pipelines, secrets, observability, and the unglamorous
  migrations nobody wants to touch. I enjoy starting a platform from an empty AWS account
  just as much as untangling a legacy one.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Senior%20Platform%20Engineer-%2F%20SRE-2496ED?style=flat-square" alt="Role" />
  <img src="https://img.shields.io/badge/Reliability-at%20scale-success?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Based%20in-Barcelona%20%F0%9F%87%AA%F0%9F%87%B8-orange?style=flat-square" alt="Location" />
</p>

---

### 🛠️ What I work on

- **Infrastructure as code.** Terraform and Terragrunt, remote state, domain-scoped modules with their own CI and versioned releases. If it isn't reproducible, it isn't done.
- **GitOps and delivery.** Reusable Argo CD setups (a Terraform module plus a Helm chart, RBAC, deploy-with-rollback) rolled out across every environment.
- **Reliability.** SLO-based alerting instead of arbitrary thresholds, error budgets, runbooks, and the occasional deep dive into a sync failure that's hiding three layers down.
- **Security and compliance.** Vault and the Vault Secrets Operator, WAF rules, private CDN origins, Falco, and enough evidence to get through a SOC2 audit.
- **Cost.** Re-architecting the expensive parts (ingestion, CI) so they cost less and do more.

---

### 🚩 Some things I've built

- **A GitOps platform, rebuilt three times.** Atlantis first, then an in-house replacement, now Argo CD — I built each one, migrated to it, and tore down the last. Five environments, Vault-sourced credentials, an ECR token rotator to work around the 12h OCI expiry, RBAC, rollback.
- **Fivetran → Airbyte.** Stood up our own ingestion platform on Kubernetes, Terraform and Helm to take back control of the data pipeline. It handles 2 TB+ datasets and knocked about **$200K/year** off the bill.
- **Security hardening.** Moved every service onto Vault + VSO, wrote a reusable WAF module, migrated CloudFront to private S3 origins, deployed Falco, and put together the evidence for **SOC2 Type 1**.
- **An internal developer platform.** A Next.js portal that lets the data team spin database replicas up and down through auto-generated infra PRs, with Slack and Datadog wired in — so nobody has to ping an SRE for it.
- **CI on Kubernetes.** Moved all our GitHub Actions off EC2 runners onto a dedicated EKS cluster so large parallel builds stopped being a bottleneck.

---

### 🧰 Tech I reach for

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

### 🧪 On the side

A couple of things I run outside of work:

- **[Smashbase](https://smashbase.io)** — a SaaS for running padel tournaments and leagues: registrations, groups, brackets, AI-assisted scheduling and live results. It's a proper multi-service app (API, payments, background workers, and both an admin and a public frontend) and I own all of it.
- **[Femutech](https://femutech.com)** — my AWS consultancy, focused on trimming cloud bills (usually up to ~50%) without hurting performance. It's the day job turned into a service.

---

### 📈 Right now

Mostly Argo CD and GitOps at the moment, plus tightening up our SLOs and error-budget process. On the side I'm pulling the same production habits — IaC, secrets, observability — into my own projects.

---

### 📫 Say hi

<p align="left">
  <a href="mailto:info@xurtasun.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/xurtasun"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>
