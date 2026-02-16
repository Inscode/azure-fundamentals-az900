## What are Access Tiers?
Access tiers in Azure Storage allow you to store data based on how frequently it is accessed. They help optimize storage costs by placing data in the appropriate tier depending on usage patterns.

Think of it as:
> Choosing the right storage “temperature” — frequently used data stays hot, rarely used data moves to colder, cheaper storage.

---

## Why Access Tiers Matter
- Reduce storage costs
- Improve cost management
- Match storage to usage patterns
- Support lifecycle management
- Enable long-term data retention

---

## Benefits of Access Tiers
- Cost optimization by storing data in lower-cost tiers
- Flexibility to move data between tiers
- High durability across all tiers
- Efficient data lifecycle management

---

## Types of Access Tiers

### Hot Tier
- Designed for frequently accessed data
- Higher storage cost but low access cost
- Ideal for active workloads

**Use Cases:**
- Streaming content
- Website assets
- Active datasets
- Frequently accessed files

---

### Cool Tier
- For infrequently accessed data
- Lower storage cost than Hot
- Higher access cost
- Minimum storage duration: 30 days

**Use Cases:**
- Short-term backups
- Disaster recovery data
- Older project files

---

### Cold Tier
- Rarely accessed data
- Lower storage cost with moderate retrieval cost
- Minimum storage duration: ~30 days

**Use Cases:**
- Compliance data accessed occasionally
- Historical logs
- Long-term backups with occasional access

---

### Archive Tier
- Lowest storage cost
- Highest retrieval cost
- Data must be rehydrated before access
- Minimum storage duration: 180 days

**Use Cases:**
- Long-term retention
- Regulatory archives
- Legal records
- Audit logs

---

## Cost vs Access Pattern

| Tier | Storage Cost | Access Cost | Access Frequency |
|-----|-------------|------------|-----------------|
| Hot | High | Low | Frequent |
| Cool | Medium | Medium | Infrequent |
| Cold | Low | Medium | Rare |
| Archive | Lowest | High | Very Rare |

---

## AWS Comparison (High Level)

| Azure | AWS Equivalent |
|------|---------------|
| Hot | S3 Standard |
| Cool | S3 Standard-IA |
| Cold | S3 Glacier Instant Retrieval |
| Archive | S3 Glacier / Deep Archive |

---

## When to Use Access Tiers
- Optimize storage spending
- Manage growing data volumes
- Implement lifecycle policies
- Store backup and archive data efficiently

---

## AZ-900 Exam Tips
- Hot = frequently accessed
- Cool/Cold = infrequent access
- Archive = long-term storage
- Archive requires rehydration before access
- Moving data between tiers helps reduce cost

---

## Quick Summary
- Access tiers help balance cost and performance.
- Choose tier based on access frequency.
- Lifecycle policies automate movement between tiers.
- Archive tier is best for long-term retention.
