# Day 03 — AZ-900 Notes — Compute and Networking Introduction

## What is Compute in Azure?
Compute refers to cloud resources that run applications, workloads, and services. Instead of buying physical servers, you use Azure’s on-demand compute power.

### Key Benefits
- No hardware management
- Scalability on demand
- Pay-as-you-go pricing
- High availability

---

## Azure Compute Services

### Virtual Machines (VMs)
- Infrastructure as a Service (IaaS)
- Full control over OS and software
- Used for lift-and-shift workloads

### Azure App Service
- Platform as a Service (PaaS)
- Host web apps and APIs without managing servers

### Azure Functions
- Serverless compute
- Run code triggered by events
- Pay only when code runs

### Containers
- Lightweight app packaging
- Run using Azure Container Instances or Kubernetes (AKS)

---

## What is Networking in Azure?
Networking enables communication between Azure resources, the internet, and on-premises environments.

---

## Azure Networking Services

### Virtual Network (VNet)
- Private network in Azure
- Isolated environment for resources
- Similar to a traditional data center network

### Subnets
- Divide VNet into smaller segments
- Improve organization and security

### Network Security Groups (NSG)
- Control inbound and outbound traffic
- Act like a firewall at subnet or NIC level

### Azure Load Balancer
- Distributes traffic across multiple resources
- Improves availability and performance

### VPN Gateway
- Secure connection between on-premises and Azure

### Azure DNS
- Resolves domain names to IP addresses

---

## Public vs Private Access
- **Public IP:** Accessible from internet
- **Private IP:** Internal communication only

---

## High Availability Concepts
- Availability Zones — separate physical locations
- Availability Sets — protect against hardware failure
- Load balancing — distribute workload

---

## Common AZ-900 Exam Points
- Know difference between IaaS, PaaS, Serverless
- Understand purpose of VNet and Subnets
- Know what NSG does
- Understand when to use VMs vs App Service vs Functions
- Recognize load balancer role

---

## Quick Summary
- Compute runs applications in Azure
- Networking connects and secures resources
- VNets provide isolation
- NSGs control traffic
- Multiple compute options exist based on control level
