# AZ-900 — Azure Virtual Machines (VM) and Virtual Machine Scale Sets (VMSS)

## Azure Virtual Machines (VM)

### What is an Azure VM?
Azure Virtual Machines are on-demand, scalable computing resources that give you full control over the operating system and environment. They are an Infrastructure as a Service (IaaS) offering.

### Key Characteristics
- Full control over OS (Windows or Linux)
- Install custom software and configurations
- Pay-as-you-go pricing
- Suitable for lift-and-shift migrations

### Common Use Cases
- Running legacy applications
- Development and testing environments
- Hosting databases or enterprise apps
- Custom workloads requiring OS access

### Benefits
- High flexibility
- Supports many VM sizes
- Integration with Azure networking and storage
- Supports backup and disaster recovery

### AWS Comparison
- Azure VM ≈ AWS EC2

---

## Virtual Machine Scale Sets (VMSS)

### What is VMSS?
Virtual Machine Scale Sets allow you to deploy and manage a group of identical, load-balanced VMs that can automatically scale based on demand or schedule.

### Key Characteristics
- Automatic scaling (scale out/in)
- High availability by default
- Load balancing integration
- Centralized management of many VMs

### Common Use Cases
- Web applications with variable traffic
- Microservices architecture
- Batch processing workloads
- Large-scale distributed systems

### Benefits
- Handles traffic spikes automatically
- Reduces manual management
- Improves reliability
- Cost efficient (scale down when idle)

### AWS Comparison
- VMSS ≈ Auto Scaling Group (ASG)

---

## VM vs VMSS — Quick Comparison

| Feature | Virtual Machine | VM Scale Set |
|--------|----------------|-------------|
| Number of instances | Single | Multiple identical |
| Scaling | Manual | Automatic |
| Use case | Custom workloads | High traffic apps |
| Management | Individual | Centralized |
| Availability | Depends on setup | Built-in resilience |

---

## AZ-900 Exam Tips
- Use VMs when you need full control over the OS.
- Use VM Scale Sets when you need automatic scaling.
- VMSS improves availability and handles load changes.
- Understand difference between manual vs automatic scaling.

---

## Quick Summary
- Azure VM = single virtual server.
- VMSS = group of VMs that scale automatically.
- Both are compute services under IaaS.
