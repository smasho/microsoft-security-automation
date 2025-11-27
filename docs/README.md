# Microsoft Security Automation

![status](https://img.shields.io/badge/status-active-green)
![license](https://img.shields.io/badge/license-MIT-blue)
![technology-PowerShell](https://img.shields.io/badge/tech-PowerShell-purple)
![technology-AzureCLI](https://img.shields.io/badge/tech-AzCLI-teal)
![technology-Terraform](https://img.shields.io/badge/tech-Terraform-593dfc)
![technology-API](https://img.shields.io/badge/tech-REST%20API-orange)

> **Automate, standardize, and scale Microsoft security deployments** using PowerShell, Azure CLI, Terraform, and REST APIs.

This repository provides production-grade examples, scripts, Infrastructure-as-Code modules, and API samples for deploying and configuring major Microsoft security products across Azure and Microsoft 365.

---

# 📑 Table of Contents

- [✨ Overview](#-overview)
- [🔐 Supported Microsoft Security Products](#-supported-microsoft-security-products)
- [📁 Repository Structure](#-repository-structure)
- [🚀 Features](#-features)
- [🧩 Use Cases](#-use-cases)
- [⚙️ Getting Started](#️-getting-started)
- [📘 Documentation](#-documentation)
- [🏗️ Architecture Overview](#️-architecture-overview)
- [🛣️ Roadmap](#️-roadmap)
- [📜 License](#-license)

---

# ✨ Overview

**Microsoft Security Automation** is a unified toolkit designed to simplify and accelerate the deployment of security services in Azure and Microsoft 365.

It provides ready-to-use automation for:

- Creating core security resources  
- Enabling product features at scale  
- Configuring baselines and recommended settings  
- Bootstrapping SOC and SecOps environments  
- Interacting with Microsoft Graph & Security APIs  

The goal is to help:

- Cloud Security Engineers
- DevSecOps Engineers  
- Managed Security Service Providers  
- SOC Teams  
- Architects    

... quickly adopt and standardize Microsoft security technologies.

---

# 🔐 Supported Microsoft Security Products

This repository includes automations for:

### **Azure Security**
- **Microsoft Defender for Cloud**  
- **Microsoft Sentinel**  
- Azure Resource Manager Security  
- Azure Entra (AAD) security settings  

### **Microsoft 365 Security**
- **Microsoft Defender XDR (Microsoft 365 Defender)**  
- **Microsoft Purview (future)**  

### **Modern Security Operations**
- **Microsoft Copilot for Security** (API examples when available)  
- Incident handling automation  
- Security baselines  

### **API Coverage**
- Microsoft Graph API  
- Graph Security API  
- Azure Resource Manager REST API  
- Defender-specific APIs

---

# 📁 Repository Structure

```text
microsoft-security-automation/
├─ docs/
│  └─ README.md
│
├─ powershell/
│  ├─ defender-xdr/
│  ├─ defender-for-cloud/
│  ├─ sentinel/
│  └─ copilot-security/
│
├─ azcli/
│  ├─ defender-xdr/
│  ├─ defender-for-cloud/
│  ├─ sentinel/
│  └─ copilot-security/
│
├─ terraform/
│  ├─ defender-for-cloud/
│  ├─ sentinel/
│  └─ shared/modules/
│
├─ api/
│  ├─ azure/
│  ├─ m365/
│  ├─ shared/auth/
│  └─ postman/
│
└─ .github/workflows/
   └─ lint-and-validate.yml
```

---

# 🚀 Features

✔️ PowerShell, Azure CLI, Terraform, and REST API examples  
✔️ Modular building blocks for security deployments  
✔️ Realistic enterprise-level scenarios  
✔️ Unified authentication patterns  
✔️ CI-ready and DevSecOps friendly  
✔️ Documentation designed for teams  
✔️ Postman collections and .http samples  
✔️ One repository for all Microsoft security automations  

---

# 🧩 Use Cases

This repository covers:  
**🛡️ Security Deployment**
- Deploy a Log Analytics workspace
- Enable Microsoft Sentinel
- Activate Microsoft Defender for Cloud plans

**📦 Security Configuration**
- Configure M365 Defender settings (API)  
- Onboard data connectors  
- Deploy analytics rules, automation rules (Sentinel)  
- Configure advanced Defender XDR features  

**⚡ SOC / SecOps Automation**
- API-based incident management  
- Automated alert enrichment  
- Retrieve threat intelligence  
- Custom workflows for triage  

**💠 Governance / Landing Zones**
- Standardized security baseline
- Multi-subscription deployment strategies
- Compliance & policy automation  

---

# ⚙️ Getting Started  

| Component  | Install  |
| :-------------| :-------------------------------------------------------------------------------  |
| PowerShell 7+ | https://learn.microsoft.com/powershell                                            |
| Azure CLI     | https://learn.microsoft.com/en-us/cli/azure/install-azure-cli                     |
| Terraform     | https://developer.hashicorp.com/terraform/tutorials/azure-get-started/install-cli |

---

# 📘 Documentation

All documentation is available under /docs:
- **HOWTO-usage.md** — how to run scripts

Additional product-specific documentation is inside each technology folder.

---

# 🏗️ Architecture Overview

The repository follows these principles:
### Modular
Scripts and IaC modules are deliberately small and composable.

### Cross-Technology
Terraform = infra  
PowerShell / CLI = configuration  
REST API = advanced or missing features  

### Scalable
Designed for:
- Multi-subscription
- Multi-tenant

### API-First
Where Microsoft exposes APIs, we provide examples (Graph, REST, Security API).

---

# 🛣️ Roadmap
### In Progress
- Creating and configuring Log Analytics Workpsace
- Enabling and configuring Microsoft Sentinel

### Planned
- Enabling Microsoft Defender Plans

---

# 📜 License
This project is licensed under the MIT License.  
You’re free to use, modify, and integrate the content into your own environments and pipelines.
