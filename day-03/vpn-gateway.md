
# AZ-900 — Azure VPN Gateway (Concept + Real-World Scenario)

## What is Azure VPN Gateway?
Azure VPN Gateway is a networking service that allows you to securely connect your on-premises network or individual devices to Azure using an encrypted connection over the internet.

Think of it as:
> A secure tunnel between your office and the cloud.

---

## Big Idea
VPN Gateway extends your existing network into Azure so resources can communicate privately and securely.

---

## Real-World Scenario — Private Tunnel to Cloud Office

Imagine your company has a physical office and also runs applications in Azure.

You build a secure tunnel so employees in the office can access cloud resources safely without exposing traffic to the public internet.

Employees work as if everything is on the same network.

---

## What VPN Gateway Does
- Encrypts network traffic
- Connects on-premises networks to Azure
- Enables hybrid cloud environments
- Provides secure remote access
- Protects data in transit

---

## Types of VPN Connections

### Site-to-Site VPN
Connects an entire on-premises network to Azure.

Use case:
- Company data center connected to Azure resources.

---

### Point-to-Site VPN
Allows individual users to connect securely from their devices.

Use case:
- Remote employees working from home.

---

### VNet-to-VNet VPN
Connects multiple Azure virtual networks.

Use case:
- Communication between different Azure regions.

---

## How VPN Gateway Works (Simple Flow)
1. Deploy VPN Gateway in Azure
2. Configure connection with on-premises network or client
3. Establish encrypted tunnel
4. Secure communication begins

---

## When to Use VPN Gateway
- Hybrid cloud setups
- Secure remote access
- Connecting branch offices
- Testing cloud connectivity
- Extending corporate network

---

## VPN vs ExpressRoute (Quick Comparison)

| Feature | VPN | ExpressRoute |
|--------|----|-------------|
| Connection type | Over public internet | Private dedicated link |
| Cost | Lower | Higher |
| Setup speed | Faster | Slower |
| Use case | Small to medium workloads | Enterprise high-performance |

---

## Benefits
- Secure encrypted communication
- Cost-effective connectivity
- Easy to set up
- Flexible access options

---

## AZ-900 Exam Tips
- VPN Gateway connects networks securely over the internet.
- Supports Site-to-Site, Point-to-Site, and VNet-to-VNet.
- Commonly used for hybrid cloud scenarios.
- Uses encryption to protect data.

---

## Quick Summary
- VPN Gateway creates a secure tunnel to Azure.
- Enables private communication between networks.
- Important component for hybrid networking.
