<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   ███╗   ███╗██╗██╗  ██╗██╗██████╗                          ║
║   ████╗ ████║██║██║  ██║██║██╔══██╗                         ║
║   ██╔████╔██║██║███████║██║██████╔╝                         ║
║   ██║╚██╔╝██║██║██╔══██║██║██╔══██╗                         ║
║   ██║ ╚═╝ ██║██║██║  ██║██║██║  ██║                         ║
║   ╚═╝     ╚═╝╚═╝╚═╝  ╚═╝╚═╝╚═╝  ╚═╝  MENON                 ║
║                                                              ║
║          DevOps Engineer  ·  Cloud Infrastructure           ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=500&lines=Infrastructure+as+Code+%7C+Terraform;AWS+%7C+ECS+%7C+Fargate+%7C+ECR;CI%2FCD+Pipelines+%7C+GitHub+Actions;Docker+%7C+Kubernetes+%7C+Containerisation;LLM+%2B+IaC+%7C+AI-Driven+Infrastructure)](https://git.io/typing-svg)

</div>

---

## `$ whoami`

```yaml
name: Mihir Menon
handle: mihirxtc
location: Leicester, United Kingdom
focus: DevOps | Cloud Infrastructure | IaC | CI/CD
currently_building:
  - Production-grade AWS deployments with Terraform
  - LLM-assisted Infrastructure-as-Code generation & validation
learning:
  - Kubernetes (CKA prep)
  - AWS Solutions Architect Associate
open_to: Junior DevOps / Cloud Engineer roles
```

---

## `$ cat tech_stack.yaml`

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white)

**CI/CD & Automation**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-%23FF9900.svg?style=flat-square&logo=amazon-ecs&logoColor=white)
![Amazon ECR](https://img.shields.io/badge/Amazon_ECR-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)

**Languages & Tools**

![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)

---

## `$ ls -la projects/`

### 🚀 [devops-proj1-nodejs-app](https://github.com/mihirxtc/devops-proj1-nodejs-app)
> **Production-grade AWS cloud-native pipeline**

A fully automated deployment of a containerised Node.js app to **AWS ECS Fargate** — infrastructure managed entirely as code.

```
AWS ECS Fargate  ←  GitHub Actions CI/CD  ←  Docker Build
       ↑                    ↑
   Amazon ECR          OIDC Auth (no static keys)
       ↑
   Terraform IaC (VPC · Subnets · IAM · ECS Task Definitions)
```

**What makes it real-world:**
- 🔐 Uses **OIDC federation** instead of long-lived AWS access keys
- 🏗️ Full IaC with **Terraform** — VPC, subnets, IAM, ECS, ECR
- 🔄 Rolling deployments via GitHub Actions on every push
- 🛠️ Documented incident recovery: state corruption, IAM conflicts, Terraform version mismatches

`HCL` `JavaScript` `Dockerfile` `GitHub Actions` `AWS`

---

### 🤖 [llms-assisted-iac-generation-and-validation](https://github.com/mihirxtc/llms-assisted-iac-generation-and-validation)
> **LLM-driven Infrastructure-as-Code framework**

A framework combining **Large Language Models** with automated validation tooling to generate syntactically correct and security-compliant Terraform — reducing IaC deployment errors at their source.

`JavaScript` `Terraform` `LLM` `IaC` `Security`

---

### 📦 [nodejs-app](https://github.com/mihirxtc/nodejs-app)
> **Containerised Node.js app for Docker & Kubernetes deployments**

Sample application serving as a base for container orchestration demos.

`JavaScript` `Dockerfile`

---

### 📚 [100xdevs_Cohort](https://github.com/mihirxtc/100xdevs_Cohort)
> **Full-stack engineering cohort — 11 weeks of consistent learning**

Week-by-week progression through JavaScript, TypeScript, Node.js, React, and backend fundamentals.

`JavaScript` `TypeScript` `CSS` `HTML` `Node.js`

---

## `$ cat architecture.ascii`

```
┌─────────────────────────────────────────────────────────┐
│                   GitHub Repository                     │
│                   (Source of Truth)                     │
└───────────────────────┬─────────────────────────────────┘
                        │ git push
                        ▼
┌─────────────────────────────────────────────────────────┐
│               GitHub Actions CI/CD                      │
│  ┌──────────┐   ┌──────────┐   ┌────────────────────┐  │
│  │  Build   │──▶│   Test   │──▶│  Deploy to AWS ECS  │  │
│  │ Docker   │   │          │   │  (OIDC, no keys)   │  │
│  └──────────┘   └──────────┘   └────────────────────┘  │
└─────────────────────────────────────────────────────────┘
                        │
          ┌─────────────┴──────────────┐
          ▼                            ▼
┌─────────────────┐          ┌─────────────────────┐
│   Amazon ECR    │          │   Terraform State   │
│  (Image Store)  │          │   (S3 Backend)      │
└────────┬────────┘          └─────────────────────┘
         │
         ▼
┌─────────────────────────────────────────────────────────┐
│                     AWS ECS Fargate                     │
│  ┌──────────────────────────────────────────────────┐   │
│  │                Custom VPC                        │   │
│  │  ┌─────────────────┐   ┌──────────────────────┐  │   │
│  │  │  Public Subnet  │   │  ECS Task Definition  │  │   │
│  │  │  (ALB / IGW)    │──▶│  (Node.js container) │  │   │
│  │  └─────────────────┘   └──────────────────────┘  │   │
│  │                  IAM (Least Privilege)            │   │
│  └──────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────┘
```

---

## `$ git log --stats`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mihirxtc&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mihirxtc&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=c9d1d9)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=mihirxtc&theme=tokyonight&hide_border=true&background=0d1117&ring=00d9ff&fire=00d9ff&currStreakLabel=00d9ff)

</div>

---

## `$ cat goals_2025.txt`

```bash
[ ] AWS Solutions Architect Associate
[ ] Certified Kubernetes Administrator (CKA)
[ ] Multi-cloud experience (Azure)
[ ] Open source contributions
[✓] End-to-end AWS ECS + Terraform pipeline
[✓] OIDC-secured CI/CD (no long-lived credentials)
[✓] LLM-assisted IaC generation framework
```

---

## `$ cat contact.json`

```json
{
  "linkedin": "linkedin.com/in/mihirmenon",
  "twitter":  "@mihirxtc",
  "github":   "github.com/mihirxtc",
  "open_to":  "Junior DevOps / Cloud Engineer roles",
  "location": "Ahmedabad, Gujarat · open to relocation"
}
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mihirmenon/)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/mihirxtc)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mihirxtc)

---

```
"Infrastructure is just software with consequences."
```

![Profile Views](https://komarev.com/ghpvc/?username=mihirxtc&color=00d9ff&style=flat-square&label=profile+views)

</div>
