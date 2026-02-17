## Multi-Factor Authentication (MFA)

Multi-Factor Authentication (MFA) is a security feature that requires users to provide two or more verification methods to confirm their identity before accessing resources.

It adds an extra layer of protection beyond just a password.

Think of it as:
> Something you know + Something you have + Something you are.

---

## Why MFA is Important

- Protects against password theft
- Reduces risk of account compromise
- Strengthens identity security
- Helps prevent unauthorized access
- Essential for cloud environments

---

## MFA in Azure

- Provided through Microsoft Entra ID
- Can be enforced using Conditional Access policies
- Supports user and admin accounts
- Works across Azure services and applications

---

## Benefits

### Increased Security
- Adds extra verification step
- Protects sensitive resources
- Mitigates phishing risks

### Flexibility
- Multiple verification methods
- Adaptive authentication options
- Works across devices and locations

### Compliance
- Helps meet regulatory requirements
- Supports security standards
- Improves audit readiness

---

## Common MFA Methods

### Phone Calls
- Automated call for verification
- User confirms login via phone

### Text Messages (SMS)
- One-time code sent to mobile
- User enters code to authenticate

### Mobile App Notifications
- Push notification approval
- Microsoft Authenticator commonly used

### Biometrics
- Fingerprint or face recognition
- Device-based authentication

---

## Use Cases

### Securing Cloud Access
- Protect Azure Portal access
- Secure admin operations
- Prevent unauthorized logins

### Remote Work Security
- Ensure safe access from external networks
- Protect VPN and cloud apps
- Secure distributed workforce

---

## Real Example

Scenario:
An employee logs into Azure Portal.

Step 1 — Enter username and password  
Step 2 — Receive push notification on mobile  
Step 3 — Approve login  

Access granted securely.

---

## AWS Comparison

| Concept | Azure | AWS |
|--------|------|-----|
| MFA service | Entra MFA | AWS MFA |
| Policy enforcement | Conditional Access | IAM Policies |
| Authenticator app | Microsoft Authenticator | Virtual MFA device |

---

## AZ-900 Exam Tips

- MFA adds an extra verification factor.
- Implemented via Microsoft Entra ID.
- Used to improve security posture.
- Often combined with Conditional Access.
- Strongly recommended for admin accounts.

---

## Quick Summary

- MFA strengthens authentication security.
- Requires multiple verification factors.
- Helps protect identities and cloud resources.
