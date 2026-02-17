# Microsoft Entra External Identities (B2B & B2C) — Notes

## Overview
Microsoft Entra External Identities allows organizations to securely collaborate with external users such as customers, partners, vendors, and suppliers.

It supports two main models:
- B2C — Customer identity and access for consumer apps
- B2B — Partner and external collaboration

---

# B2C (Business to Consumer)

## What is B2C?
Microsoft Entra External Identities B2C enables organizations to manage customer identities for public-facing applications.

It provides sign-up, sign-in, and profile management with customizable experiences.

---

## Key Features

### Customizable User Journeys
- Customize sign-up and sign-in flows
- Add branding and custom policies
- Define user attributes and workflows

### Social Identity Providers
- Allow login with Google, Facebook, Microsoft, etc.
- Reduce friction during registration
- Improve user adoption

### Strong Authentication
- Supports MFA and password policies
- Protects customer accounts from compromise

---

## Benefits

### Enhanced User Experience
- Smooth and branded login experience
- Simplified onboarding

### Scalability
- Handles millions of users
- Built for high-traffic consumer apps

### Security and Compliance
- Identity protection and monitoring
- Meets regulatory requirements

---

## Use Cases

### Consumer-Facing App Hosting
- Mobile apps
- Customer portals
- Public websites

### E-commerce, Gaming, Consumer Apps
- Online stores with customer accounts
- Subscription platforms
- Gaming platforms

---

# B2B (Business to Business)

## What is B2B?
Microsoft Entra External Identities B2B enables secure collaboration with external organizations.

External users can access resources using their own credentials while administrators maintain control.

---

## Key Features

### Cross-Organization Collaboration
- Invite partners and vendors
- Share apps and resources securely

### Self-Service Sign-Up
- External users can onboard themselves
- Reduces admin workload

### Customizable User Experience
- Control access policies
- Apply Conditional Access and MFA

---

## Benefits

### Enhanced Security and Compliance
- Enforce policies for external users
- Monitor access activity

### Simplified Management
- Centralized identity governance
- Easy user lifecycle management

### Improved Collaboration
- Seamless project sharing
- Secure partner access

---

## Use Cases

### Collaborative Project Sharing
- Joint development projects
- Shared document repositories

### External Partner Resource Access
- Vendors accessing internal systems
- Contractors accessing tools

### Customer Portal Access
- Partner dashboards
- Supplier portals

---

## Conceptual Difference: B2B vs B2C

| Aspect | B2B | B2C |
|-------|-----|-----|
| Users | Partners, vendors | Customers |
| Purpose | Collaboration | Customer authentication |
| Scale | Moderate | Massive scale |
| Identity Source | External org accounts | Social/local accounts |
| Example | Partner accessing SharePoint | Customer logging into shopping app |

---

## Simple Real Scenario

### B2C Example
An online shopping platform uses B2C so customers can:
- Sign up with Google
- Log in securely
- Manage profiles

### B2B Example
A company invites a consulting firm:
- Consultants log in with their company accounts
- Access project resources securely

---

## Key Takeaway
- B2C focuses on customer identity for apps.
- B2B focuses on secure external collaboration.
- Both integrate with Conditional Access, MFA, and security policies.
