# Azure Zero Trust — Notes

## What is Zero Trust

- Security model that assumes no user or device is trusted by default
- Every access request must be verified
- Applies to users, devices, apps, and data — inside or outside network
- Moves away from “trust inside network” model

### Classic vs Zero Trust

**Classic approach**
- Trust based on network location
- Once inside network → broad access

**Zero Trust approach**
- Verify every request
- Continuous validation
- Central policies protect resources anywhere

---

## Core Principles of Zero Trust

### 1️⃣ Verify Explicitly

- Authenticate and authorize every request
- Use signals like:
  - User identity
  - Location
  - Device health
  - Risk level
  - Application sensitivity

**Azure examples**
- Microsoft Entra ID authentication
- Conditional Access policies
- MFA enforcement

---

### 2️⃣ Use Least Privilege Access

- Grant minimum permissions required
- Reduce attack surface
- Limit duration of access

#### Key practices

- Just-in-time (JIT) access
- Just-enough access (JEA)
- Risk-based adaptive policies

**Azure services**
- Azure RBAC
- Privileged Identity Management (PIM)
- Conditional Access

---

### 3️⃣ Assume Breach

- Design systems assuming attackers may be inside
- Monitor continuously
- Limit lateral movement

#### Controls

- Segment access by:
  - Network
  - User
  - Device
- Enforce encryption
- Use analytics for threat detection

**Azure services**
- Microsoft Defender for Cloud
- Microsoft Sentinel
- Network segmentation
- Encryption at rest and in transit

---

## Zero Trust Implementation Areas in Azure

- Identity → Entra ID, MFA, Conditional Access
- Devices → Intune, device compliance
- Applications → App proxy, secure access
- Data → Encryption, data classification
- Infrastructure → Network security groups, segmentation
- Monitoring → Defender, Sentinel logs

---

## Why Zero Trust Matters

- Supports remote work and cloud environments
- Protects against credential theft
- Limits damage during breaches
- Enables strong compliance posture

---

## Quick Summary

- Never trust, always verify
- Grant minimal access
- Monitor continuously
- Protect resources regardless of location
