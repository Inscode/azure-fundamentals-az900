# Defense in Depth (Azure Security Model)

## Overview
Defense in Depth is a layered security strategy used in Azure to protect systems, data, and workloads.  
Each layer adds protection so that if one control fails, others continue to defend.

---

## Security Layers

### Physical Security
- Protects hardware and data centers.
- Controls physical access to servers and facilities.
- Includes surveillance, access badges, and secure buildings.

### Identity and Access Management
- Ensures only authorized users access resources.
- Uses authentication, authorization, MFA, and policies.
- Managed through Microsoft Entra ID.

### Perimeter Security
- Protects against external attacks.
- Uses firewalls and DDoS protection.
- Filters incoming traffic.

### Network Security
- Segments networks to limit attack spread.
- Uses NSGs, virtual networks, and private endpoints.
- Controls communication between resources.

### Compute Security
- Protects VMs, containers, and serverless workloads.
- Includes patching, endpoint protection, and monitoring.
- Secures runtime environments.

### Application Security
- Secures application code and APIs.
- Uses secure development practices and vulnerability management.
- Protects against common attacks.

### Data Security
- Protects data at rest and in transit.
- Uses encryption, access controls, and backups.
- Ensures confidentiality and integrity.

---

## Benefits
- Robust multi-layer protection.
- Reduces risk of breaches.
- Supports compliance requirements.
- Provides holistic security coverage.

---

## Key Takeaway
Security in Azure is implemented through multiple layers — not a single control — ensuring stronger protection against threats.
