## Microsoft Entra Domain Services

Microsoft Entra Domain Services (formerly Azure AD Domain Services) is a managed domain service that provides traditional Active Directory features in Azure without requiring you to deploy or manage domain controllers.

Think of it as:
> Active Directory in the cloud, fully managed by Microsoft.

---

## What It Provides

- Managed domain environment in Azure
- Domain join support for virtual machines
- Group Policy management
- LDAP, Kerberos, and NTLM authentication
- Integration with Microsoft Entra ID
- High availability by default

---

## Key Capabilities

### Managed Domain Service
- Microsoft manages domain controllers
- Automatic patching and updates
- Built-in backup and monitoring

### Scalable and Highly Available
- Runs across availability zones
- Handles replication automatically
- Supports growing workloads

### Compatibility with Windows Server
- Supports traditional Windows workloads
- Enables legacy application support
- Works with enterprise authentication protocols

---

## Key Features

### Domain Join
- Azure VMs can join the managed domain
- Enables centralized authentication
- Supports domain-based applications

### Group Policy
- Apply security configurations
- Enforce password policies
- Manage system settings

### LDAP and Kerberos / NTLM Authentication
- Supports enterprise authentication protocols
- Enables legacy app compatibility
- Secure identity validation

### Integrated Management
- Managed via Azure portal
- No infrastructure maintenance
- Centralized control

---

## Benefits

### Simplified Administration
- No need to manage domain controllers
- Reduced operational overhead
- Easier deployment

### Scalability and Reliability
- Automatic scaling
- High availability built in
- Resilient architecture

### Security and Compliance
- Secure authentication mechanisms
- Built-in monitoring
- Supports enterprise security standards

---

## Use Cases

### Active Directory Migration
- Move AD-dependent workloads to Azure
- Reduce on-prem infrastructure

### Maintain Group Policy
- Enforce corporate policies in cloud workloads
- Maintain security baselines

### Authentication for Legacy Applications
- Support apps requiring LDAP or Kerberos
- Enable lift-and-shift migrations

---

## When to Use Entra Domain Services

- Applications require domain join
- Legacy workloads need LDAP or Kerberos
- Moving Windows workloads to Azure
- Reducing domain controller management
- Hybrid identity scenarios

---

## How It Fits in Azure Identity

- Microsoft Entra ID → Modern identity platform
- Entra Domain Services → Managed domain for legacy compatibility
- RBAC → Resource access control

---

## AZ-900 Exam Tips

- Provides managed Active Directory in Azure
- Supports domain join and Group Policy
- Used for legacy app authentication
- No need to deploy domain controllers
- Integrates with Entra ID

---

## Quick Summary

- Entra Domain Services brings traditional AD capabilities to Azure.
- Enables domain-based authentication without infrastructure management.
- Ideal for legacy applications and hybrid environments.
