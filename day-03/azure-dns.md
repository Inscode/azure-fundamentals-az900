# AZ-900 — Azure DNS Notes

## What is Azure DNS?
Azure DNS is a hosting service that allows you to manage DNS records using Azure infrastructure. It translates domain names (like www.example.com) into IP addresses so users can access applications and services.

Think of it as:
> The phonebook of the internet hosted in Azure.

---

## Big Idea
Azure DNS helps users find your applications by mapping human-friendly names to technical network addresses.

---

## Real-World Scenario — Finding a Website

Imagine a customer wants to visit your company website:

1. They type your domain name into a browser.
2. DNS translates the name into an IP address.
3. The browser connects to the correct server.

Azure DNS manages this mapping reliably and globally.

---

## Key Features
- Highly available and globally distributed
- Fast DNS resolution
- Supports custom domain names
- Integrated with Azure resources
- Secure and scalable

---

## What Azure DNS Can Do
- Host public DNS zones for internet-facing apps
- Host private DNS zones for internal networks
- Manage DNS records for services
- Improve application availability

---

## DNS Zones

### Public DNS Zone
Used for resolving domain names on the internet.

Example:
- Users accessing your public website.

---

### Private DNS Zone
Used within Azure virtual networks for internal name resolution.

Example:
- Communication between internal services.

---

## Common DNS Record Types

- A Record — Maps a domain to an IPv4 address
- AAAA Record — Maps to IPv6 address
- CNAME — Alias for another domain
- MX — Mail server record
- TXT — Verification and metadata
- NS — Name server record

---

## How Azure DNS Works (Simple Flow)
1. User requests a domain name
2. DNS query is sent
3. Azure DNS responds with IP address
4. Connection is established

---

## When to Use Azure DNS
- Hosting domain records
- Managing cloud applications
- Internal service discovery
- High availability DNS management

---

## Benefits
- Reliable global infrastructure
- Low latency responses
- Easy management through Azure portal
- Integration with Azure networking

---

## AZ-900 Exam Tips
- Azure DNS hosts domain names.
- Supports public and private zones.
- Helps resolve names to IP addresses.
- Used for both internet and internal networking.

---

## Quick Summary
- Azure DNS translates domain names to IP addresses.
- Provides scalable and reliable name resolution.
- Essential for accessing cloud applications.
