## What is Identity and Access Management (IAM)?
Identity and Access Management (IAM) in Azure is a framework that ensures the right people and services have appropriate access to resources. It helps control who can access Azure resources, what actions they can perform, and under what conditions.

Think of it as:
> A security system that verifies identity and enforces permissions across your cloud environment.

---

## Why IAM is Important
- Protects resources from unauthorized access
- Ensures secure authentication and authorization
- Supports least privilege access
- Helps meet compliance and security requirements
- Enables secure collaboration

---

## Core Components in Azure IAM

- **Microsoft Entra ID (Azure AD)** — Manages identities such as users, groups, and applications.
- **Role-Based Access Control (RBAC)** — Controls permissions to Azure resources.
- **Managed Identities** — Allows Azure services to authenticate securely without storing credentials.
- **Conditional Access** — Enforces security policies like MFA and device compliance.

---

## What IAM Controls
- User access to Azure portal
- Service-to-service communication
- Resource permissions
- Administrative access
- Security policies

---

## AWS Comparison (High Level)

| Concept | Azure | AWS |
|--------|------|-----|
| Identity service | Microsoft Entra ID | AWS IAM |
| Permission model | RBAC | IAM Policies |
| Service identity | Managed Identity | IAM Role |

---

## When IAM is Used
- Granting developers access to resources
- Securing applications
- Allowing services to interact securely
- Enforcing organizational security policies

---

## AZ-900 Exam Tips
- IAM ensures secure access to Azure resources.
- Entra ID handles identity.
- RBAC controls permissions.
- Managed Identity removes need for secrets.

---

## Quick Summary
- IAM controls authentication and authorization in Azure.
- Helps secure cloud environments.
- Ensures only authorized access is allowed.
