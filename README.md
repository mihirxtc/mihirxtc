<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║    ███╗   ███╗██╗██╗  ██╗██╗██████╗     ███╗   ███╗███████╗    ║
║    ████╗ ████║██║██║  ██║██║██╔══██╗    ████╗ ████║██╔════╝    ║
║    ██╔████╔██║██║███████║██║██████╔╝    ██╔████╔██║█████╗      ║
║    ██║╚██╔╝██║██║██╔══██║██║██╔══██╗    ██║╚██╔╝██║██╔══╝      ║
║    ██║ ╚═╝ ██║██║██║  ██║██║██║  ██║    ██║ ╚═╝ ██║███████╗    ║
║    ╚═╝     ╚═╝╚═╝╚═╝  ╚═╝╚═╝╚═╝  ╚═╝    ╚═╝     ╚═╝╚══════╝    ║
║                                                                  ║
║             DevOps Engineer  ·  Cloud Infrastructure            ║
║                Leicester, United Kingdom  🇬🇧                   ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2800&pause=900&color=00D9FF&center=true&vCenter=true&width=540&lines=Terraform+%7C+AWS+ECS+%7C+Fargate+%7C+ECR;GitHub+Actions+CI%2FCD+%7C+OIDC+Auth;Docker+%7C+Kubernetes+%7C+Containerisation;Infrastructure+as+Code+%7C+IaC+Automation;LLM+%2B+IaC+%7C+AI-Driven+Infrastructure)](https://git.io/typing-svg)

</div>

---

## `$ whoami`

```yaml
name        : Mihir Menon
handle      : mihirxtc
location    : Leicester, United Kingdom 🇬🇧
role        : DevOps Engineer · Cloud Infrastructure
focus       :
  - Infrastructure as Code (Terraform)
  - AWS Cloud-Native Deployments
  - CI/CD Pipeline Automation
  - AI-Assisted IaC Generation
currently   :
  studying  : AWS Solutions Architect Associate
  building  : LLM-assisted IaC validation framework
  learning  : Kubernetes (CKA track)
open_to     : Junior DevOps / Cloud Engineer roles in the UK
```

---

## `$ cat tech_stack.sh`

**☁️ Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/ECS_Fargate-%23FF9900.svg?style=flat-square&logo=amazon-ecs&logoColor=white)
![Amazon ECR](https://img.shields.io/badge/ECR-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)

**🐳 Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white)

**⚙️ CI/CD & Automation**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)

**🛠️ Languages & Tools**

![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)

---

## `$ ls -la projects/`

### ⚡ [devops-proj1-nodejs-app](https://github.com/mihirxtc/devops-proj1-nodejs-app)

> Production-grade AWS cloud-native pipeline — fully automated, zero static credentials

```
 Developer Push
      │
      ▼
 GitHub Actions ──► OIDC Auth (no long-lived keys)
      │
      ├──► Docker Build
      │
      ├──► Push to Amazon ECR
      │
      └──► Update ECS Task Definition
                  │
                  ▼
          AWS ECS Fargate
          ┌─────────────────────────────────┐
          │  Custom VPC · Public Subnets    │
          │  IAM (Least Privilege)          │
          │  Rolling Deployment             │
          └─────────────────────────────────┘

 Infrastructure : 100% Terraform IaC
 Security       : OIDC Federation — no static AWS keys
 Automation     : GitHub Actions on every push
```

**Real-world debugging documented:**
- 🔧 Resolved Terraform backend state version corruption via CLI upgrade + re-sync
- 🔁 Used `git reflog` + hard reset to recover lost infrastructure configuration
- 🔑 Manually cleared `EntityAlreadyExists` IAM conflicts in AWS Console

`HCL 81%` · `JavaScript 17%` · `Dockerfile 2%`

---

### 🤖 [llms-assisted-iac-generation-and-validation](https://github.com/mihirxtc/llms-assisted-iac-generation-and-validation)

> Using LLMs to auto-generate and validate Terraform — reduce deployment errors at source

```
  User Prompt
      │
      ▼
  LLM Generation ──► Terraform Code
                          │
                          ├──► Syntax Validation
                          ├──► Security Scanning
                          └──► Deployment-Ready IaC
```

`JavaScript` · `Terraform` · `LLM` · `Security Validation`

---

### 📦 [nodejs-app](https://github.com/mihirxtc/nodejs-app)

> Containerised Node.js application — base image for Docker & Kubernetes deployment demos

`JavaScript 80%` · `Dockerfile 20%`

---

### 📚 [100xdevs_Cohort](https://github.com/mihirxtc/100xdevs_Cohort)

> Full-stack engineering cohort — 11 weeks · 40 commits · consistent learning cadence

```
week-1 ──► week-2 ──► week-3 ──► ... ──► week-11
  JS         Node       APIs             TypeScript + React
```

`JavaScript` · `TypeScript` · `Node.js` · `CSS` · `HTML`

---

## `$ cat goals.log`

```diff
+ [DONE] End-to-end AWS ECS pipeline with Terraform
+ [DONE] OIDC-secured CI/CD — zero long-lived credentials
+ [DONE] LLM-assisted IaC generation framework (v0.1)
+ [DONE] 11-week full-stack cohort completion

! [IN PROGRESS] AWS Solutions Architect Associate
! [IN PROGRESS] Kubernetes — CKA prep
! [IN PROGRESS] LLM+IaC framework — expand validation coverage

- [PLANNED] Azure fundamentals
- [PLANNED] Prometheus + Grafana monitoring stack
- [PLANNED] First open source contribution
```

---

## `$ uptime && neofetch`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mihirxtc&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff&text_color=c9d1d9&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mihirxtc&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=c9d1d9&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=mihirxtc&theme=tokyonight&hide_border=true&background=0d1117&ring=00d9ff&fire=ff6b6b&currStreakLabel=00d9ff&sideLabels=c9d1d9&dates=8b949e)

</div>

---

## `$ cat /etc/contact`

```json
{
  "name"        : "Mihir Menon",
  "location"    : "Leicester, United Kingdom",
  "linkedin"    : "linkedin.com/in/mihirmenon",
  "twitter"     : "@mihirxtc",
  "github"      : "github.com/mihirxtc",
  "open_to"     : "Junior DevOps / Cloud Engineer roles",
  "sponsorship" : "Skilled Worker visa eligible roles welcome"
}
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mihirmenon/)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/mihirxtc)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mihirxtc)

---

```
╔══════════════════════════════════════════════════════╗
║  "Ship infrastructure, not excuses."                 ║
╚══════════════════════════════════════════════════════╝
```

![Profile Views](https://komarev.com/ghpvc/?username=mihirxtc&color=00d9ff&style=flat-square&label=profile+views)

</div>
