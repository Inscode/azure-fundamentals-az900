## What is Azure Storage?
Azure Storage is a cloud platform that provides scalable, secure, and highly available storage for different types of data including objects, files, messages, tables, and disks. It allows organizations to store and manage data without maintaining physical infrastructure.

Think of it as:
> A reliable cloud storage foundation that supports applications, backups, analytics, and disaster recovery.

---

## Storage Overview (AZ-900 Context)
The Azure Storage section introduces the core concepts required to understand how data is stored, protected, accessed, and migrated in Azure. It covers storage accounts, storage types, redundancy strategies, access tiers, and migration tools.

---

## Azure Storage Types
Azure provides multiple storage services designed for different workloads:

- **Blob Storage** — Object storage for unstructured data like images, videos, backups, and logs.
- **Azure Files** — Managed file shares accessible via SMB or NFS for shared storage scenarios.
- **Queue Storage** — Messaging storage used for asynchronous communication between application components.
- **Table Storage** — NoSQL key-value store for structured, non-relational data.
- **Disk Storage** — Persistent block storage used by virtual machines.

---

## What You Learn in This Section
- How Azure organizes storage using Storage Accounts
- Different storage types and their use cases
- How data durability is ensured with redundancy options
- How access tiers help optimize cost
- Tools available for migrating data to Azure
- Methods for managing and syncing files

---

## Why Azure Storage Matters
Nearly every cloud solution relies on storage. Whether hosting applications, storing backups, processing data, or enabling disaster recovery, Azure Storage provides the backbone for reliable data management.

---

## Common Use Cases
- Storing application data and media files
- Backup and disaster recovery
- Archiving long-term data
- Supporting analytics workloads
- Migrating on-premises data to the cloud
- Sharing files across teams and services

---

## AWS Comparison (High Level)

| Concept | Azure | AWS Equivalent |
|--------|------|----------------|
| Object storage | Azure Blob Storage | Amazon S3 |
| File shares | Azure Files | Amazon EFS / FSx |
| Messaging storage | Azure Queue Storage | Amazon SQS |
| NoSQL storage | Azure Table Storage | Amazon DynamoDB |
| VM disks | Azure Disk Storage | Amazon EBS |

---

## AZ-900 Exam Perspective
Expect to understand:
- Basic purpose of Azure Storage
- Storage types and when to use them
- Importance of durability and availability
- High-level differences between storage options

---

## Quick Summary
- Azure Storage is a foundational cloud service for storing and managing data.
- Supports Blob, Files, Queue, Table, and Disk storage.
- Designed for scalability, durability, and security.
- Essential for most Azure workloads.
