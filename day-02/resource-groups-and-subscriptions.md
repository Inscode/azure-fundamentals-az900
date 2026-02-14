# Azure Resource Groups and Subscriptions (AZ-900 Day 02)

## 📌 Overview
Azure uses subscriptions and resource groups to organize, manage, and control access to resources.

They help with billing, governance, and lifecycle management.

---

## 📦 Azure Subscriptions

### What is a Subscription?
A subscription is a logical container used to provision Azure resources.

It acts as:
- Billing boundary
- Access control boundary
- Resource management boundary

### Why Use Subscriptions?
- Separate environments (dev, test, prod)
- Track costs
- Apply policies
- Manage access with RBAC

---

## 🧾 Key Features
- Each subscription has its own billing
- Resources must belong to a subscription
- Supports quotas and limits
- Can have multiple subscriptions per account

---

## 🗂️ Resource Groups

### What is a Resource Group?
A resource group is a container that holds related Azure resources for a solution.

Examples of resources:
- Virtual machines
- Storage accounts
- Databases
- Networking components

---

## 🎯 Purpose of Resource Groups
- Organize resources logically
- Manage lifecycle together
- Apply access control
- Deploy and monitor as a unit

---

## 🔄 Lifecycle Concept
If you delete a resource group → all resources inside are deleted.

This is useful for temporary environments.

---

## 📊 Subscription vs Resource Group

| Feature | Subscription | Resource Group |
|--------|-------------|---------------|
| Scope | Higher level | Lower level |
| Purpose | Billing & governance | Resource organization |
| Contains | Resource groups | Resources |

---

## 🧠 Best Practices
- Group resources by lifecycle
- Use naming conventions
- Separate environments into subscriptions
- Apply RBAC at appropriate level

---

## 🎯 Exam Tips (AZ-900)

- Subscription = Billing boundary
- Resource group = Logical container
- Resources must belong to one resource group
- Resource groups cannot span subscriptions

---

## 📝 Quick Summary

- Subscription manages billing and access
- Resource groups organize resources
- Deleting resource group deletes all resources
