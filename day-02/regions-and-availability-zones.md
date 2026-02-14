# Azure Regions and Availability Zones (AZ-900 Day 02)

## 📌 Overview
Azure organizes its global infrastructure into regions and availability zones to provide high availability, fault tolerance, and low latency for applications.

Understanding how these work is critical for designing resilient solutions and for AZ-900 exam concepts.

---

## 🌍 Azure Regions

### What is a Region?
An Azure region is a geographical area containing one or more datacenters connected through a low-latency network.

Microsoft deploys Azure services in regions worldwide so customers can run workloads close to their users.

### Key Characteristics
- Provides data residency and compliance options
- Reduces latency by placing resources near users
- Supports disaster recovery strategies
- Regions are independent from each other

### Examples of Regions
- East US
- West Europe
- Southeast Asia
- Australia East

---

## 🔗 Region Pairs

Each Azure region is paired with another region within the same geography.

### Benefits of Region Pairs
- Automatic platform updates rolled out sequentially
- Disaster recovery support
- Priority recovery during outages
- Data replication strategies

Example:
- East US ↔ West US
- North Europe ↔ West Europe

---

## 🏢 Availability Zones

### What is an Availability Zone?
Availability Zones are physically separate datacenters within a region.

Each zone has:
- Independent power
- Cooling
- Networking

This protects applications from datacenter failures.

---

## ✅ Benefits of Availability Zones
- High availability
- Fault isolation
- Improved resiliency
- Supports mission-critical workloads

---

## 🧠 When to Use Availability Zones
Use zones when:
- Running production workloads
- Need high uptime SLAs
- Building fault-tolerant architectures

---

## 📊 Region vs Availability Zone

| Feature | Region | Availability Zone |
|--------|-------|------------------|
| Scope | Geographic area | Datacenter within region |
| Purpose | Service location | Fault isolation |
| Use case | Deploy workloads globally | High availability |

---

## 🎯 Exam Tips (AZ-900)

- Regions = Geographic locations
- Availability Zones = Separate datacenters
- Zone failures do not impact other zones
- Region pairs support disaster recovery

---

## 📝 Quick Summary

- Regions help with latency and compliance
- Availability Zones improve resiliency
- Use multiple zones for high availability
