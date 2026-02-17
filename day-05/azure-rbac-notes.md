# Azure Role-Based Access Control (RBAC)

## What is Azure RBAC?
- Azure RBAC is an authorization system used to manage access to Azure resources.
- It defines **who can do what on which resource**.
- Works together with **Microsoft Entra ID (authentication)** — Entra ID verifies identity, RBAC grants permissions.
- Helps enforce least privilege and secure resource operations.

---

## How RBAC Works (Core Concept)
RBAC is based on three questions:

- **Who** → User, group, service principal, or managed identity
- **What** → Role (permissions)
- **Where** → Scope (subscription, resource group, resource)

Example:
- DevOps engineer → Contributor role → Resource Group

---

## Key Components

### 1. Security Principal (Who)
- User
- Group
- Application / Service Principal
- Managed Identity

### 2. Role Definition (What)
Defines allowed actions.

Types:
- Built-in roles
- Custom roles

### 3. Scope (Where)
Permission boundary:

- Management group
- Subscription
- Resource group
- Resource

---

## Key Features

### Predefined Roles
- Owner → Full access + can grant permissions
- Contributor → Manage resources but cannot grant access
- Reader → View only
- User Access Administrator → Manage permissions

### Custom Roles
- Create fine-grained permissions for specific needs.

### Scoped Access
- Assign permissions at different levels to control blast radius.

---

## Benefits

### Least Privilege
- Users get only necessary permissions.

### Streamlined Management
- Centralized access control across Azure.

### Improved Compliance
- Auditable permissions help meet security standards.

---

## Common Use Cases

### Multi-User Environments
- Teams working on shared subscriptions.

### Large Organizations
- Different departments get scoped access.

### Secure Projects
- Restrict production resource access to limited admins.

---

## Real-World Scenarios

- A developer can deploy apps but cannot delete production databases.
- Finance team can view billing but cannot modify infrastructure.
- External contractor gets temporary Reader access.

---

## Relationship with Microsoft Entra ID

- Entra ID → Authentication (login)
- RBAC → Authorization (permissions)

Think:
> Entra ID opens the door, RBAC decides what you can do inside.

---

## Interview Tips

- Know difference between RBAC and Entra roles.
- Understand scope hierarchy.
- Explain least privilege principle.
- Be able to give real examples of role assignments.
- Mention built-in vs custom roles.

---

## Quick Summary

- RBAC controls access in Azure.
- Uses roles + scope + principals.
- Works with Entra ID.
- Enables secure, scalable permission management.
