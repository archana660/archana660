<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&color=gradient&customColorList=0%3A0d1117%2C100%3A1f6feb&section=header&text=ARCHANA%20DWIVEDI&fontSize=42&fontColor=FFFFFF&fontAlignY=35&desc=Sr.%20DevOps%20Engineer&descSize=18&descAlignY=58" alt="Archana Dwivedi — Sr. DevOps Engineer" />

**Azure Cloud • Terraform • CI/CD • Kubernetes • DevSecOps**

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=700&color=58A6FF&center=true&vCenter=true&width=520&lines=Azure+Cloud;Terraform;Infrastructure+as+Code;CI%2FCD+Automation;Kubernetes+%2F+AKS;DevSecOps" alt="Focus areas" />

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/archana660)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/archana-dwivedi231/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arch2731@gmail.com)

<img src="https://komarev.com/ghpvc/?username=archana660&label=Profile+Views&color=0D1117&style=flat-square" alt="Profile views" />

</div>

---

## 👩‍💻 WHOAMI

<table><tr><td width="62%" valign="top">

Senior DevOps Engineer with 8 years of overall IT experience, including 4+ years specializing in Azure Cloud, Infrastructure as Code (Terraform), Azure DevOps and CI/CD automation. Skilled in Docker, Kubernetes (AKS), GitHub Actions and DevSecOps practices, designing secure, scalable cloud architectures with security gates embedded across the delivery pipeline.

📍 Delhi NCR, India

</td><td width="38%" valign="top"><img src="https://project--e57879aa-e77b-4f7c-b079-b1cdf6cb957b.lovable.app/__l5e/assets-v1/535f7f72-de27-41b4-9492-c6701b80c3a0/devops-woman.png" width="100%" alt="DevOps engineer at work" /></td></tr></table>

---

## ⚡ SYSTEM STATUS

| Layer | Technology | Focus |
| --- | --- | --- |
| Cloud | Microsoft Azure | Cloud Infrastructure |
| IaC | Terraform | Infrastructure Automation |
| CI/CD | Azure DevOps | Pipeline Automation |
| CI/CD | GitHub Actions | Automation |
| Containers | Docker | Containerization |
| Kubernetes | AKS | Container Orchestration |
| Security | tfsec / Checkov / TFLint | Security Gates |
| Monitoring | Azure Monitor | Observability |

---

## 💼 EXPERIENCE

### Sr. DevOps Engineer — Apex Websoft, Noida
`March 2025 – Present`

- Architected modular Terraform frameworks for Azure (VNets, NSGs, VMs, Storage, Key Vault) using reusable child modules and environment-specific .tfvars, cutting provisioning effort by ~50%.
- Implemented Azure Blob remote backend with state locking and workspace isolation, eliminating state conflicts across dev, test, staging and production.
- Built multi-stage Azure DevOps YAML pipelines with reusable templates (init, validate, tflint, tfsec, plan, approval gate, apply), enforcing zero infrastructure drift.
- Configured GitHub Actions with OIDC Workload Identity Federation for keyless Azure authentication, removing all long-lived service principal secrets.

### DevOps Engineer — Benthon Labs, Noida
`April 2023 – Dec 2024`

- Built reusable Terraform module libraries for Azure compute, hub-spoke VNet peering, Private DNS Zones and storage, adopted across 4 product teams.
- Maintained Azure DevOps and GitHub Actions pipelines with tfsec/Checkov security gates and multi-environment approval stages, reducing manual handoffs.
- Configured Key Vault-linked Variable Groups for secure secret injection in Azure DevOps pipelines, eliminating hardcoded credentials.
- Administered Linux systems with Azure Monitor / Log Analytics alerting; led patch management and incident response.

### Cloud Engineer (Azure) — ARP Technologies, Noida
`Sept 2022 – Feb 2023`

- Managed Azure deployments (VMs, storage, networking, load balancers) with RBAC and Managed Identities as first-class access control via the Azure Portal.
- Worked with Azure Monitor and Log Analytics to review resource health and alerts.

### Linux System Administrator — DriveIT Digital, Noida
`April 2019 – August 2022`

- Managed Linux servers, including user administration, package installation, patch management, backups and system health monitoring.
- Performed server provisioning and access management; supported application deployments and coordinated with cross-functional teams during production releases.

---

## 🔄 DEVOPS PIPELINE

```text
CODE → GIT → GITHUB → CI/CD
                     ↓
              VALIDATE / SECURITY
                     ↓
                 TERRAFORM
                     ↓
                   AZURE
                     ↓
                MONITORING
```

`Azure DevOps` · `GitHub Actions` · `Terraform` · `TFLint` · `tfsec` · `Checkov` · `Azure Monitor` · `Log Analytics`

---

## ☁️ CLOUD INFRASTRUCTURE

```text
Microsoft Azure
│
├── Networking
│   ├── VNets
│   ├── Subnets
│   ├── NSGs
│   ├── Azure Firewall
│   └── Private Endpoints
│
├── Compute & Containers
│   ├── Virtual Machines
│   ├── App Service
│   └── AKS
│
├── Security
│   ├── Key Vault
│   ├── RBAC
│   ├── Managed Identities
│   ├── Azure Policy
│   └── PIM
│
└── Monitoring
    ├── Azure Monitor
    ├── Log Analytics
    └── Application Insights
```

---

## 🏛️ AZURE LANDING ZONE

```text
Azure Landing Zone
        │
        ├── Governance   → Azure Policy
        │
        ├── Identity     → Microsoft Entra ID · RBAC · PIM · Managed Identities
        │
        ├── Networking   → VNets · NSGs · Azure Firewall · Private Endpoints
        │
        ├── Security     → Key Vault · Defender for Cloud
        │
        └── Workloads    → App Service · AKS · Virtual Machines
```

---

## 🏗️ INFRASTRUCTURE AS CODE

```text
Terraform
│
├── Modules
├── Variables
├── Resources
├── Workspaces
├── Remote State
└── Azure Blob Backend
```

```bash
terraform init
terraform validate
terraform plan
terraform apply
```

---

## 🧩 TERRAFORM MODULES

```text
Root Module
     │
     ├── Network Module    (VNets · Subnets · NSGs)
     ├── Compute Module    (Virtual Machines)
     ├── Storage Module    (Storage Accounts)
     ├── Security Module   (RBAC · Managed Identities)
     └── Key Vault Module  (Secrets)
```

---

## 🔐 DEVSECOPS

```text
CODE
  ↓
VALIDATE        → TFLint
  ↓
IaC SECURITY    → tfsec · Checkov · Terrascan
  ↓
CODE SECURITY   → SonarQube · Snyk · TruffleHog · OWASP ZAP (SAST / DAST)
  ↓
APPROVAL
  ↓
DEPLOY
```

---

## ☸️ KUBERNETES / AKS

```text
AKS
│
├── Nodes
│
├── Pods
│
├── Services
│
└── Helm
```

---

## 📊 MONITORING & OBSERVABILITY

```text
Azure Resources
      ↓
Azure Monitor
      ↓
Log Analytics
      ↓
Application Insights
      ↓
Prometheus / Grafana
```

---

## 🛠️ TECH STACK

**Cloud**

`Microsoft Azure` · `Azure Landing Zone` · `Azure Resource Manager (ARM)`

**Infrastructure as Code**

`Terraform` · `Terraform Modules` · `Remote State Management` · `Workspaces` · `Azure Blob Backend`

**CI/CD**

`Azure DevOps` · `GitHub Actions` · `YAML Pipelines`

**Containers & Orchestration**

`Docker` · `Kubernetes (AKS)` · `Helm`

**Security & DevSecOps**

`tfsec` · `Checkov` · `TFLint` · `Terrascan` · `SonarQube` · `Snyk` · `TruffleHog` · `OWASP ZAP` · `SAST` · `DAST`

**Azure Services**

`VNets` · `Subnets` · `NSG` · `Azure Firewall` · `Private Endpoints` · `App Service` · `API Management (APIM)` · `Storage Account` · `Azure SQL` · `Key Vault` · `Azure Monitor` · `Log Analytics` · `Defender for Cloud` · `Cost Management`

**Identity & Governance**

`Microsoft Entra ID` · `RBAC` · `Managed Identities` · `Azure Policy` · `PIM`

**Monitoring**

`Prometheus` · `Grafana` · `Azure Monitor` · `Log Analytics` · `Application Insights`

**Scripting & Automation**

`PowerShell` · `Bash` · `YAML` · `HCL` · `Azure CLI` · `Git` · `Ansible (Basics)`

**Data & Integration**

`Azure Data Factory` · `Azure Logic Apps`

**AI & Emerging Tech**

`MCP (Model Context Protocol) Servers` · `GitHub Copilot` · `AI-Assisted DevOps Automation` · `Prompt Engineering (Basics)` · `LLM-based Tooling (Basics)`

---

## 🚀 FEATURED PROJECTS

_Projects can be added from verified repository links._

---

## 📈 GITHUB COMMAND CENTER

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=archana660&show_icons=true&hide_border=true&theme=github_dark" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=archana660&layout=compact&hide_border=true&theme=github_dark" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=archana660&hide_border=true&theme=github_dark" alt="Contribution streak" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=archana660&hide_border=true&theme=github-compact" alt="Contribution activity" />

</div>

---

## 💻 TERMINAL

```text
archana@devops:~$ whoami
Archana Dwivedi

archana@devops:~$ role
Sr. DevOps Engineer

archana@devops:~$ cloud
Microsoft Azure

archana@devops:~$ iac
Terraform

archana@devops:~$ cicd
Azure DevOps / GitHub Actions

archana@devops:~$ containers
Docker / Kubernetes (AKS) / Helm

archana@devops:~$ security
DevSecOps — tfsec / Checkov / TFLint

archana@devops:~$ monitoring
Azure Monitor / Log Analytics
```

<div align="center"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=460&lines=terraform+plan+-out%3Dtfplan;az+aks+get-credentials;kubectl+get+pods+-A" alt="Terminal animation" /></div>

---

## 🧭 CAREER JOURNEY

```text
Linux System Administrator  (April 2019 – August 2022)
        ↓
Cloud Engineer (Azure)  (Sept 2022 – Feb 2023)
        ↓
DevOps Engineer  (April 2023 – Dec 2024)
        ↓
Sr. DevOps Engineer  (March 2025 – Present)
```

---

## 🎓 EDUCATION

**B.Tech — Computer Science**  
UPTU, Moradabad  
`August 2010 – June 2014`

---

## 📫 CONNECT

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/archana660)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/archana-dwivedi231/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arch2731@gmail.com)

</div>

---

<div align="center">

```text
Thanks for visiting my GitHub ⭐

BUILD → AUTOMATE → SECURE → DEPLOY → IMPROVE
```

</div>
