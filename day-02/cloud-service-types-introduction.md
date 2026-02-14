# Cloud Service Types — Introduction (AZ-900 Day 02)

## 📌 Overview
Cloud service types describe how much responsibility you keep vs what the cloud provider (like Azure) manages. Understanding these models is fundamental for AZ-900 because it helps you choose the right solution based on control, flexibility, and operational effort.

The three primary cloud service types are:

- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)

They exist on a spectrum from more control → less management.

---

## 🏗️ Infrastructure as a Service (IaaS)

### What it is
IaaS provides basic building blocks like virtual machines, storage, and networking. You manage the OS, runtime, and applications.

### Key Idea
“Lift and shift” — move existing workloads to the cloud with minimal changes.

### You manage
- Operating system
- Applications
- Data
- Runtime
- Security configuration

### Azure examples
- Azure Virtual Machines
- Azure Virtual Network
- Azure Load Balancer

### When to use
- Need full control
- Custom environments
- Legacy applications

---

## ⚙️ Platform as a Service (PaaS)

### What it is
PaaS provides a platform for building and deploying applications without managing underlying infrastructure.

### Key Idea
Focus on code — Azure handles OS, patching, and scaling.

### You manage
- Applications
- Data
- Configuration

### Azure examples
- Azure App Service
- Azure SQL Database
- Azure Functions

### When to use
- Rapid development
- Web apps and APIs
- Dev/test environments

---

## 💻 Software as a Service (SaaS)

### What it is
Fully managed applications delivered over the internet. You simply use the software.

### Key Idea
No infrastructure or platform management — just configure and use.

### You manage
- User settings
- Data

### Azure/Microsoft examples
- Microsoft 365
- Outlook Online
- Dynamics 365

### When to use
- Email and collaboration
- CRM systems
- Ready-to-use business apps

---

## 📊 Responsibility Model (Shared Responsibility Concept)

| Layer | On-Prem | IaaS | PaaS | SaaS |
|------|--------|------|------|------|
| Applications | You | You | You | Provider |
| Data | You | You | You | You |
| Runtime | You | You | Provider | Provider |
| OS | You | You | Provider | Provider |
| Virtualization | You | Provider | Provider | Provider |
| Hardware | You | Provider | Provider | Provider |

---

## 🎯 Exam Tips (AZ-900)

- IaaS = Most control, most management
- SaaS = Least control, least management
- PaaS = Best for developers
- Know real Azure examples
- Understand shared responsibility

---

## 📝 Quick Summary

- IaaS → Rent infrastructure
- PaaS → Deploy applications
- SaaS → Use software

---

