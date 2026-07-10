# AI Revenue Intelligence & CRM Automation Agent

An AI-powered CRM automation workflow built with **n8n**, **Groq AI**, **Google Sheets**, and **HubSpot CRM** that automates company research, lead qualification, CRM record creation, and sales pipeline management.

---

# 📌 Project Overview

Sales and GTM teams spend significant time researching companies, qualifying leads, creating CRM records, and preparing for customer conversations.

This project automates those repetitive tasks using AI.

The workflow reads company information from Google Sheets, performs AI-powered company research using Groq, converts the research into structured JSON, creates CRM records automatically in HubSpot, and stores AI-generated insights for future reference.

This project demonstrates practical AI workflow automation for Revenue Operations, GTM Engineering, Solution Engineering, and CRM Automation.

---

# ✨ Features

* 🤖 AI-powered company research
* 🏢 Company profile generation
* 📊 Business summary generation
* 🏭 Industry identification
* 👥 Target customer identification
* 💼 Products & Services extraction
* ⚠️ Pain point analysis
* 🚀 Opportunity identification
* 💡 AI solution recommendations
* 🎯 AI Lead Score generation
* 🔥 Lead Priority classification
* 📄 JSON transformation
* 📚 AI Research Repository
* 🏢 Automatic Company creation in HubSpot
* 👤 Automatic Contact creation in HubSpot
* 💼 Automatic Deal creation in HubSpot
* 📈 CRM Activity logging
* 🔁 Batch processing of multiple companies

---

# 🛠 Tech Stack

* n8n
* Groq AI (LLM)
* Google Sheets
* HubSpot CRM
* JavaScript
* JSON

---

# 🏗 Workflow Architecture

```text
Manual Trigger
      │
      ▼
Google Sheet (Lead List)
      │
      ▼
Loop Over Items
      │
      ▼
AI Revenue Intelligence Agent (Groq)
      │
      ▼
Research JSON Formatter
      ├────────────► Google Sheet
      │             (AI Research Repository)
      │
      ▼
HubSpot Create Company
      │
      ▼
HubSpot Create Contact
      │
      ▼
HubSpot Create Deal
      │
      ▼
Google Sheet
(CRM & Outreach History)
```

---

# 📂 Project Structure

```
AI-Revenue-Intelligence-CRM-Automation-Agent/

│
├── README.md
├── LICENSE
├── AI-Revenue-Intelligence-CRM-Automation-Agent-v1.json
│
└── screenshots
    ├── workflow-overview.png
    ├── ai-research-output.png
    ├── code-node-output.png
    ├── hubspot-company.png
    ├── hubspot-contact.png
    ├── hubspot-deal.png
    ├── research-repository.png
    └── crm-history.png
```

---

# ⚙️ Workflow Steps

## 1. Lead Intake

Reads company names and website URLs from Google Sheets.

---

## 2. AI Company Research

Groq AI analyzes each company and generates:

* Company Name
* Website
* Industry
* Business Summary
* Target Customers
* Products & Services
* Pain Points
* Opportunities
* Recommended Solution
* Lead Score
* Priority

---

## 3. JSON Transformation

The AI response is converted into structured JSON using a JavaScript Code Node for downstream automation.

---

## 4. AI Research Repository

The structured AI research is automatically stored in Google Sheets for future reference and reporting.

---

## 5. HubSpot CRM Automation

The workflow automatically creates:

* Company
* Contact
* Deal

inside HubSpot CRM.

---

## 6. CRM Activity Repository

The workflow records CRM activity, including company, contact, deal, lead score, and priority, into a second Google Sheet.

---

# 📸 Screenshots

## Workflow Overview

(https://github.com/archanakrishnan094-max/AI-Revenue-Intelligence-CRM-Automation-Agent/blob/main/Screenshots/workflow-overview.png.png)

---

## AI Research Output

(https://github.com/archanakrishnan094-max/AI-Revenue-Intelligence-CRM-Automation-Agent/blob/main/Screenshots/ai-research-output.png.png)

---

## Code Node JSON Output

*(Insert screenshot)*

---

## HubSpot Company Record

*(Insert screenshot)*

---

## HubSpot Contact Record

*(Insert screenshot)*

---

## HubSpot Deal Record

*(Insert screenshot)*

---

## Google Sheet – AI Research Repository

*(Insert screenshot)*

---

## Google Sheet – CRM & Outreach History

*(Insert screenshot)*

---

# 💡 Key Learnings

Through this project I gained hands-on experience with:

* AI workflow automation
* Prompt engineering
* Groq LLM integration
* JSON transformation
* HubSpot CRM automation
* Google Sheets automation
* Multi-step workflow orchestration
* CRM data management
* AI-powered lead qualification

---

# 🚀 Future Improvements (Version 2)

Planned enhancements include:

* Clay data enrichment
* Duplicate company detection
* HubSpot update workflows
* AI meeting preparation reports
* Personalized AI cold email generation
* Gmail automation
* HubSpot Notes automation
* CRM relationship associations
* Advanced lead scoring

---

# 👩‍💻 Author

**Archana Krishnan**

AI Workflow Builder | AI GTM Enthusiast |Electrical & Electronics Engineer

* AI Workflow Automation
* HubSpot CRM Automation
* n8n
* Groq AI
* Prompt Engineering
* Revenue Intelligence
* Solution Engineering

---

# 📄 License

This project is licensed under the MIT License.

