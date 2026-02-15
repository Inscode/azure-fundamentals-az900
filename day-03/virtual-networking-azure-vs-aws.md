# AZ-900 — Virtual Networking (Azure vs AWS) with Real-World Scenarios

## Big Idea
Virtual networking is the process of building and managing your network infrastructure in the cloud. It allows you to securely connect resources, control traffic, and design network architecture similar to a physical data center.

Think of it as building your company’s network in the cloud.

---

## Real-World Analogy — Company Office Building

Imagine moving your company to a new office building:

- Building → Virtual network
- Floors → Subnets
- Security guards → Firewall rules
- Doors → Endpoints
- Internet connection → Gateway
- Private tunnel to HQ → VPN

This is how virtual networking works in the cloud.

---

## Core Mapping — Azure vs AWS

| Concept | Azure | AWS | Real World Meaning |
|--------|------|-----|-------------------|
| Private network | Virtual Network (VNet) | VPC | Office building |
| Subdivision | Subnet | Subnet | Floors or departments |
| Security rules | Network Security Group (NSG) | Security Groups / NACL | Security guards |
| Internet access | Internet Gateway | Internet Gateway | Door to internet |
| Secure connection | VPN Gateway | VPN | Private tunnel |
| Dedicated connection | ExpressRoute | Direct Connect | Private leased line |
| Traffic distribution | Azure Load Balancer | Elastic Load Balancer | Reception desk |
| Private service access | Private Endpoint | PrivateLink | Private entrance |

---

## Key Concepts

### Virtual Network (VNet)
A private, isolated network in Azure where resources like VMs and services communicate securely.

Purpose:
- Define IP address space
- Isolate workloads
- Control connectivity

---

### Subnets
Subnets divide a virtual network into smaller segments.

Benefits:
- Organize resources
- Apply security rules
- Separate application tiers (web, app, database)

---

### Network Security Groups (NSG)
NSGs control inbound and outbound traffic using rules.

Examples:
- Allow web traffic (port 80/443)
- Block unauthorized access
- Restrict database connections

---

### Internet Connectivity
Resources can access the internet using public IP addresses and gateways.

---

### VPN Gateway
Creates an encrypted tunnel between on-premises networks and Azure.

Use when:
- Extending corporate network to cloud
- Hybrid environments

---

### ExpressRoute
Provides a private dedicated connection between your data center and Azure.

Benefits:
- Higher reliability
- Lower latency
- More security

---

### Load Balancer
Distributes incoming traffic across multiple servers to improve availability and performance.

---

### Private Endpoint
Allows secure access to Azure services without exposing them to the public internet.

---

## Real Scenario — Web Application Architecture

A company builds an online store:

1. Web servers in a public subnet
2. Application servers in a private subnet
3. Database in a restricted subnet
4. NSG controls traffic between tiers
5. Load balancer distributes user requests
6. VPN connects corporate office
7. Private endpoint secures storage

---

## When to Use What

| Need | Use |
|-----|----|
| Create isolated network | Virtual Network |
| Separate workloads | Subnets |
| Control traffic | NSG |
| Connect on-premises | VPN Gateway |
| Private high-speed link | ExpressRoute |
| Secure service access | Private Endpoint |
| Distribute traffic | Load Balancer |

---

## AZ-900 Exam Tips
- VNet is equivalent to AWS VPC.
- NSG controls network traffic.
- VPN connects on-premises to Azure.
- ExpressRoute provides private connectivity.
- Subnets help segment workloads.
- Private Endpoint keeps traffic off the internet.

---

## Quick Summary
- Virtual networking enables secure communication in the cloud.
- Azure and AWS networking concepts are very similar.
- Proper network design improves security, performance, and scalability.
