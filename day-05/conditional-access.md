## Conditional Access

Conditional Access is a security feature in Microsoft Entra ID that controls access to applications and resources based on specific conditions like user identity, location, device status, and risk level.

It works like:
> If certain conditions are met → then allow, require MFA, or block access.

Often called:
> The policy engine of Zero Trust security.

---

## How Conditional Access Works

1. User attempts to sign in
2. Signals are evaluated (user, device, location, risk)
3. Policy is applied
4. Access decision is enforced:
   - Allow access
   - Require MFA
   - Block access

---

## Signals Used in Conditional Access

- User or group identity
- Device compliance or health
- Location (IP or region)
- Application being accessed
- Real-time risk detection

---

## Access Decisions

- Allow access
- Require Multi-Factor Authentication
- Require compliant device
- Block access

---

## Key Features

### User and Group-Based Policies
- Target specific users or roles
- Apply policies to admins or departments
- Control access by identity

### Location-Based Policies
- Restrict access by country or network
- Block risky regions
- Allow trusted locations

### Device-Based Policies
- Require managed or compliant devices
- Enforce endpoint security
- Protect corporate resources

### Risk-Based Policies
- Respond to suspicious login behavior
- Detect unusual sign-ins
- Trigger additional verification

---

## Benefits

### Enhanced Security
- Protects against identity attacks
- Reduces unauthorized access
- Supports Zero Trust model

### Flexibility and Control
- Granular policy configuration
- Adaptive security enforcement
- Customizable rules

### Streamlined User Experience
- Minimal friction for trusted users
- Stronger checks only when needed
- Intelligent access decisions

---

## Use Cases

### Protecting Sensitive Data
- Require MFA for financial systems
- Restrict admin access
- Secure confidential workloads

### Remote Work and BYOD Security
- Allow access only from compliant devices
- Enforce policies for remote users
- Secure hybrid workforce

---

## Real Example

Scenario:
An employee signs in from a new country.

Policy evaluation:
- Location is unfamiliar
- Risk detected

Action:
- Require MFA before access

If risk is high:
- Block login

---

## Relationship with MFA

- Conditional Access decides when MFA is required
- MFA verifies identity
- Together they strengthen security

---

## Azure Components Involved

- Microsoft Entra ID → Identity and policy engine
- MFA → Additional verification
- RBAC → Permission control
- Identity Protection → Risk signals

---

## AWS Comparison (High Level)

| Concept | Azure | AWS |
|--------|------|-----|
| Conditional policies | Conditional Access | IAM Conditions |
| Risk-based login | Entra Identity Protection | AWS GuardDuty signals |
| Require MFA | Conditional Access rules | IAM MFA enforcement |

---

## AZ-900 Exam Tips

- Conditional Access = If-Then policy engine.
- Uses signals like user, device, and location.
- Can require MFA or block access.
- Part of Zero Trust security.
- Works with Entra ID.

---

## Quick Summary

- Conditional Access controls how and when users access resources.
- Evaluates context before granting access.
- Helps enforce strong security policies.
