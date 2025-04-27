
# 🇳🇬 Unified Zeta Administration Management System (UZAMS)

**Version 1.0 - Legacy Data Retrieval Platform**  
**Developed for:** Nigeria Customs Service (NCS)  
**Lead Officer:** AC Osamwonyi Ehigie Uzamere (OC Cybersecurity, Tincan Island Command)

---

## 📜 Overview

**UZAMS** is a custom-built legacy data retrieval and administration system for the Nigeria Customs Service. It enables efficient search, visualization, and export of trade records—including **Single Goods Declarations (SGD)**, **Pre-Arrival Assessment Reports (PAAR)**, and **Form M**—stored from **2018 to 2025** in **PostgreSQL databases** or **Excel files**.

This project is part of the broader NCS modernization and data governance initiative, designed to improve transparency, intelligence-driven analysis, and operational efficiency.

---

## ⚙️ Tech Stack

| Component      | Technology         |
|----------------|--------------------|
| **Frontend**   | React.js (JavaScript) |
| **Backend**    | ASP.NET Core (C#) with ADO.NET |
| **Database**   | PostgreSQL, Excel Integration (via EPPlus/NPOI) |
| **Authentication** | Custom Role-Based Access (Planned: Azure AD) |
| **Deployment** | IIS / Docker / Cloud or On-Prem Infrastructure |

---

## 📁 Project Structure

```
ncs-uzams/
├── backend/               # ASP.NET Core APIs
├── frontend/              # React frontend application
├── database/              # PostgreSQL scripts, seed data, Excel samples
├── docs/                  # SRS, Roadmaps, Policy References
├── .gitignore
├── README.md
└── LICENSE
```

---

## 🚀 Core Features

- 🔐 **Login Module** with role-based interface
- 🧭 **Dashboard Navigation** to all modules
- 📄 **SGD Search Interface** (Import & Export with alternate search: TIN, License No.)
- 📑 **PAAR Retrieval Interface**
- 🧾 **Form M Access Interface**
- 📊 **Structured Results Table** with export options (PDF, CSV, Excel)
- 🕵️ **Audit Logging** *(Planned in v1.1)*
- 🧠 **Risk Intelligence Modules** *(Planned for v2.0)*

---

## 🛠️ Setup & Installation

### Prerequisites

- .NET 7 SDK
- Node.js (v16+)
- PostgreSQL Server
- Visual Studio / VS Code

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

### Backend Setup

```bash
cd backend
dotnet restore
dotnet build
dotnet run
```

---

## 🧪 Testing

- **Frontend**: Jest + React Testing Library
- **Backend**: xUnit / NUnit
- **Postman** collections in `/docs/api-tests`

---

## 📤 Deployment

Deployment steps will vary based on environment (IIS, Docker, Azure). See `/docs/deployment.md` for full instructions.

---

## 📌 Versioning

This project follows Semantic Versioning.  
**Current version**: `v1.0.0` – MVP (SGD/PAAR/Form M Search Only)

---

## 🗺️ Roadmap

| Version | Milestone |
|---------|-----------|
| `v1.0`  | Legacy Data Search MVP |
| `v1.1`  | Audit Logs, Authentication Improvements |
| `v2.0`  | Risk Management, Examination, Exit & Post-Clearance Modules |

---

## 👥 Contributors

- 👤 **Osamwonyi Ehigie Uzamere** — _Lead Architect, Nigeria Customs Service_
- 👤 [Developer Name(s)] — _Frontend/Backend/Database Engineers_

---

## 🔐 License

This project is proprietary to the **Nigeria Customs Service (NCS)**. Redistribution without authorization is prohibited.

---

## 📞 Contact

For internal inquiries and technical assistance, please contact:  
📧 `uzams.support@ncs.gov.ng` *(placeholder email)*  
📍 Cybersecurity Unit, Tincan Island Command, Nigeria Customs Service

---

> “In preserving our past, we empower our future.”  
> — *UZAMS Team*
