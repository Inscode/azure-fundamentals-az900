# AZ-900 — Azure Functions Notes

## What is Azure Functions?
Azure Functions is a serverless compute service that allows you to run small pieces of code without managing servers. The code runs automatically in response to events or triggers.

Think of it as:
> Run code only when needed — Azure handles the infrastructure.

---

## Key Features
- Serverless (no server management)
- Event-driven execution
- Automatic scaling
- Pay only when code runs
- Supports multiple programming languages (.NET, Python, JavaScript, Java)

---

## Common Triggers
Azure Functions can run when specific events occur, such as:

- HTTP requests
- File uploads to storage
- Timer schedules
- Messages in queues
- Database changes
- Event Grid notifications

---

## Use Cases
- Automation tasks
- Data processing
- Scheduled jobs
- Backend APIs
- Real-time event handling
- Integration workflows

---

## How Azure Functions Works (Simple Flow)
1. Event occurs (trigger)
2. Function executes code
3. Output is sent to another service or user

---

## Benefits
- No infrastructure management
- Scales automatically
- Cost efficient for intermittent workloads
- Fast development and deployment

---

## When to Use Azure Functions
- When workloads are event-driven
- When tasks run occasionally
- When you want to minimize costs
- When building lightweight APIs or automation

---

## Azure Functions vs Virtual Machines

| Feature | Azure Functions | Virtual Machines |
|--------|----------------|----------------|
| Server management | Not required | Required |
| Scaling | Automatic | Manual or configured |
| Execution | Event-based | Always running |
| Cost model | Pay per execution | Pay for uptime |

---

## AZ-900 Exam Tips
- Azure Functions is a serverless compute service.
- Runs code based on triggers.
- Automatically scales.
- Ideal for short-lived tasks.

---

## Quick Summary
- Azure Functions runs code without managing servers.
- Designed for event-driven workloads.
- Helps build scalable and cost-effective solutions.
