# 🛡️ RoleGuard (Community Edition)

> **Zero-Trust, 100% Client-Side AWS IAM Security Linter**  
> Audit cloud configurations locally in your browser memory. No APIs, no backend servers, no data leakage.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 🚀 Why RoleGuard?

Cloud security audits often present a **Privacy & Latency Paradox**: traditional SaaS audit tools require uploading sensitive IAM policies, Terraform files, or CloudFormation templates to third-party servers.

**RoleGuard fixes this entirely.** Operating 100% client-side inside standard browser memory, RoleGuard parses your infrastructure files locally to detect privilege escalation vectors before deployment.

---

## ⚡ Features (Community vs Pro)

| Feature | Community (Free) | Pro Version ($39) |
| :--- | :---: | :---: |
| **100% Offline / Client-Side Execution** | ✅ | ✅ |
| **AWS IAM JSON Parsing** | ✅ | ✅ |
| **Top 10 IAM Privilege Escalation Detection** | ✅ | ✅ |
| **Terraform (`.tf`) Engine** | ❌ | ✅ |
| **CloudFormation (`.yaml`) Engine** | ❌ | ✅ |
| **One-Click Automated Remediation Code** | ❌ | ✅ |
| **Client-Side JSON Audit Exporter** | ❌ | ✅ |
| **Full Single-File Offline Bundle (`RoleGuard.html`)** | ❌ | ✅ |

👉 **[Upgrade to RoleGuard Pro for Complete Protection](https://leviquest662.gumroad.com/l/roleguard-pro)**

---

## 🛠️ Quick Start (Community Edition)

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/roleguard.git](https://github.com/YOUR-USERNAME/roleguard.git)
