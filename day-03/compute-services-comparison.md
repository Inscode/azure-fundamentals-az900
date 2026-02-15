

## Compute Services — A Comparison Table

| Feature / Service | Virtual Machines | Azure Virtual Desktop | Azure App Service | Containers | Azure Functions |
|-------------------|-----------------|----------------------|------------------|-----------|----------------|
| **Primary Use** | General computing, full control over OS and environment | Virtualized desktop experience | Web hosting and mobile backends | Lightweight, isolated environments for applications | Event-driven, serverless compute functions |
| **Scalability** | Manually scalable | Scalable with user demand | Autoscaling capabilities | Easily scalable, often used in microservices architecture | Automatically scales based on demand |
| **Management Overhead** | High (OS, networking, etc.) | Medium (managed by Azure, user manages apps) | Low (platform managed by Azure) | Low (minimal OS, focus on app only) | Minimal (serverless, no infrastructure management) |
| **Flexibility** | Highly customizable | Desktop experience from anywhere | Highly optimized for web apps | High for application deployment and portability | High flexibility in responding to events |
| **Ideal For** | Complex applications, full-stack control | Remote work, BYOD policies | Web applications, RESTful APIs | Microservices, rapid development/deployment | Short-lived, event-triggered tasks, microservices |
| **Pricing** | Based on compute resources, storage, and networking | Based on usage and compute resources | Based on compute resources | Based on container size and execution time | Pay-per-use based on executions and resource consumption |

---

## Quick Summary
- **Virtual Machines** → Maximum control, highest management effort.
- **Azure Virtual Desktop** → Remote desktop experience in the cloud.
- **App Service** → Easy web app hosting without managing servers.
- **Containers** → Portable, scalable application environments.
- **Azure Functions** → Event-driven serverless execution.

---

## AZ-900 Exam Tip
Understand when to choose each service based on:
- Level of control needed
- Management overhead
- Scaling requirements
- Workload type
