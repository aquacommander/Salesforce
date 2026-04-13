# 🤖 AI Lead Agent - Salesforce

[![Deployed on](https://img.shields.io/badge/Deployed%20on-Salesforce-00A1E0?logo=salesforce&logoColor=white)](https://developer.salesforce.com/)
[![API Integration](https://img.shields.io/badge/Integrated%20with-OpenAI-000000?logo=openai&logoColor=white)](https://openai.com/api)
[![Built With](https://img.shields.io/badge/Built%20With-Apex%20%26%20LWC-1798c1?logo=salesforce&logoColor=white)](https://developer.salesforce.com/docs/component-library/overview/components)
![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)

---

## ⚡ **AI-Powered Lead Scoring Engine (Salesforce + OpenAI Integration)**  

**Integrated AI-based lead scoring directly into Salesforce CRM** using **Apex REST APIs** and **Lightning Web Components (LWC)** — delivering **real-time, intelligent prioritization** of leads and **automating intent analysis** to dramatically **improve sales accuracy and focus**.  
This is the AI based System
---

🖼️ **Demo**  
<img width="1721" height="862" alt="Screenshot 2025-10-21 at 5 00 57 PM" src="https://github.com/user-attachments/assets/82483201-887e-46ba-95f2-e8b9727e5bea" />

---

<img width="1719" height="822" alt="Screenshot 2025-10-21 at 4 59 15 PM" src="https://github.com/user-attachments/assets/9e4bda3c-01aa-456d-8be5-24af1b858edc" />

---

## 🧩 Tech Highlights
- 🔗 **OpenAI API Integration** — Connects Salesforce to GPT-4 Turbo for real-time AI insights and predictive lead scoring
- 🧩 **Full-Stack Salesforce App** — Apex backend + Lightning Web Components frontend
- 🔒 **Secure API Auth** — Managed through Salesforce Named Credentials  
- ⚙️ **SOQL + REST Integration** — Seamless CRM + AI data pipeline  

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/aquacommander/salesforce.git
cd AI.salesforce.agent

# Log in to your Salesforce Developer Org
sf org login web --alias DevOrg

# Deploy backend Apex classes
sf project deploy start --source-dir force-app/main/default/classes

# Deploy Lightning Web Component
sf project deploy start --source-dir force-app/main/default/lwc/aiLeadScoring

# Open the org
sf org open

