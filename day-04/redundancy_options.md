## What are Redundancy Options?
Redundancy options in Azure Storage define how your data is replicated to protect against hardware failures, datacenter outages, or regional disasters. They ensure durability, availability, and resilience based on business requirements.

Think of it as:
> Making multiple copies of your data in different locations so it stays safe even if something fails.

---

## Why Redundancy is Important
- Protects against data loss
- Improves availability
- Supports disaster recovery
- Ensures business continuity
- Meets compliance requirements

---

## Types of Redundancy

### Locally Redundant Storage (LRS)
- Replicates data within a single datacenter
- Lowest cost option
- Protects against hardware failures
- Does not protect against zone or regional outages

**Use Case:** Dev/test workloads, temporary data, non-critical applications

---

### Zone Redundant Storage (ZRS)
- Replicates data across multiple availability zones within a region
- Protects against datacenter failure
- Provides high availability

**Use Case:** Production applications requiring high uptime

---

### Geo Redundant Storage (GRS)
- Replicates data to a secondary region
- Provides disaster recovery capability
- Secondary region not readable unless failover occurs

**Use Case:** Backup and disaster recovery scenarios

---

### Geo-Zone Redundant Storage (GZRS)
- Combines zone redundancy with geo replication
- Highest level of durability and availability

**Use Case:** Mission-critical workloads requiring maximum protection

---

## Durability Overview (Conceptual)
- LRS — High durability within one datacenter
- ZRS — Protection across zones
- GRS — Regional disaster protection
- GZRS — Maximum resilience

---

## AWS Comparison (High Level)

| Azure | AWS Equivalent |
|------|---------------|
| LRS | Single Availability Zone storage |
| ZRS | Multi-AZ storage (S3 Standard, RDS Multi-AZ) |
| GRS | Cross Region Replication |
| GZRS | Multi-AZ + Cross Region architecture |

---

## When to Choose Which
- Choose LRS for cost-sensitive workloads
- Choose ZRS for high availability within a region
- Choose GRS for disaster recovery
- Choose GZRS for critical production systems

---

## AZ-900 Exam Tips
- Higher redundancy increases cost and protection.
- Understand differences between zone and geo replication.
- Know which option protects against regional failure.
- GZRS provides the highest level of resilience.

---

## Quick Summary
- Redundancy ensures data durability and availability.
- Azure offers multiple replication strategies.
- Selection depends on cost, risk tolerance, and recovery requirements.
