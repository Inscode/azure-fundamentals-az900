## Authentication and Authorization

Authentication and Authorization are core security concepts in Azure that control how users and services access resources.

- Authentication verifies identity.
- Authorization determines permissions.

Think of it as:
> Authentication = Who are you?
> Authorization = What can you do?

---

## Authentication

Authentication is the process of confirming a user's identity before granting access.

### What it does
- Verifies user credentials
- Ensures the user is legitimate
- Prevents unauthorized access

### Common methods
- Username and password
- Multi-Factor Authentication (MFA)
- Security tokens
- Biometrics
- Certificates

### In Azure
- Handled primarily by Microsoft Entra ID
- Supports SSO and Conditional Access

---

## Authorization

Authorization defines what actions a user or service can perform after authentication.

### What it does
- Assigns permissions
- Controls resource access
- Enforces policies

### In Azure
- Implemented using:
  - Azure RBAC (Role-Based Access Control)
  - Azure Policies
  - Resource locks
  - Access rules

---

## Key Differences

| Authentication | Authorization |
|---------------|--------------|
| Confirms identity | Defines permissions |
| Happens first | Happens after authentication |
| Uses credentials | Uses roles and policies |
| Example: Login | Example: Access storage |

---

## Azure Approach

### Authentication in Azure
- Microsoft Entra ID verifies users and identities
- Supports secure login and identity federation
- Integrates with cloud and on-prem systems

### Authorization in Azure
- Azure RBAC controls access to resources
- Policies enforce governance rules
- Fine-grained permission management

---

## Benefits

### Enhanced Security
- Protects resources from unauthorized access
- Supports MFA and identity protection

### Fine-Grained Access Control
- Assign least privilege access
- Control access at resource level

### Compliance and Governance
- Enforce organizational policies
- Meet regulatory requirements

---

## Use Cases

### User Login Authentication
- Employees sign into Azure Portal
- Applications validate user identity
- Secure access to services

### Access Control for Azure Resources
- Grant developers access to resource groups
- Limit production access to admins
- Control who can deploy or manage resources

---

## Real Example

Scenario:
A developer logs into Azure.

Step 1 — Authentication:
- Entra ID verifies username + MFA.

Step 2 — Authorization:
- RBAC checks if developer can deploy resources.

Access granted or denied accordingly.

---

## AWS Comparison (High Level)

| Concept | Azure | AWS |
|--------|------|-----|
| Authentication | Microsoft Entra ID | IAM / IAM Identity Center |
| Authorization | Azure RBAC | IAM Policies |
| MFA | Entra MFA | AWS MFA |

---

## AZ-900 Exam Tips

- Authentication = identity verification.
- Authorization = permission control.
- Entra ID handles authentication.
- RBAC handles authorization.
- Always authentication before authorization.

---

## Quick Summary

- Authentication proves identity.
- Authorization controls actions.
- Both work together to secure Azure resources.
