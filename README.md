# Microsoft-AZ-305-Azure-Solutions-Architect-Expert-Study-Guide-Exam-Preparation
Independent Microsoft AZ-305 study guide covering Azure identity, governance, monitoring, storage, business continuity, networking, compute, security, architecture, labs, and exam preparation.
# Microsoft AZ-305: Azure Solutions Architect Expert Study Guide

## Introduction

This repository is an independent study guide for **Microsoft AZ-305: Designing Microsoft Azure Infrastructure Solutions**. It provides exam-focused study notes, architecture concepts, practical lab ideas, revision topics, and a structured 30-day preparation plan.

It is designed for Azure solutions architects and experienced cloud professionals who translate business and technical requirements into secure, resilient, scalable Azure solutions.

> **Current exam:** Microsoft updated the English AZ-305 exam on April 17, 2026. Always verify the latest Microsoft Learn Study Guide before scheduling the exam.

## Exam Overview

| Item | Details |
|---|---|
| Vendor | Microsoft |
| Certification | Microsoft Certified: Azure Solutions Architect Expert |
| Exam | AZ-305: Designing Microsoft Azure Infrastructure Solutions |
| Level | Advanced |
| Purpose | Design Azure and hybrid infrastructure solutions |
| Target candidates | Azure solution architects and experienced cloud professionals |
| Passing score | 700/1000 |
| Duration | 100 minutes |
| Languages | English, Japanese, Chinese (Simplified), Korean, German, French, Spanish, Portuguese (Brazil), Chinese (Traditional), Italian |
| Retirement | None currently listed |
| Prerequisite for certification | Microsoft Certified: Azure Administrator Associate (AZ-104) |

Passing AZ-305 alone does not award the Azure Solutions Architect Expert certification. Candidates must also satisfy the certification prerequisite. Microsoft currently lists Azure Administrator Associate as the prerequisite.

## Who Should Take It?

AZ-305 is intended for professionals who design cloud and hybrid solutions involving compute, networking, storage, monitoring, identity, security, governance, and business continuity.

Microsoft recommends advanced knowledge of IT operations, including networking, virtualization, identity, security, business continuity, disaster recovery, data platforms, and governance. Experience with Azure administration, Azure development, and DevOps processes is also recommended.

## Exam Objectives / Domains

The current Microsoft skills measured are:

### 1. Design Identity, Governance, and Monitoring Solutions — 25–30%

Study:

- Identity and access management
- Microsoft Entra ID
- Authentication and authorization
- Managed identities
- Azure RBAC
- Governance
- Management groups and subscriptions
- Azure Policy
- Resource organization
- Monitoring and logging
- Azure Monitor
- Log Analytics
- Application Insights
- Cost and operational considerations

### 2. Design Data Storage Solutions — 20–25%

Study:

- Azure Storage
- Blob Storage
- Azure Files
- Storage redundancy
- Storage security
- Data protection
- Azure SQL
- Azure Cosmos DB
- Azure Database services
- Data integration
- Migration requirements
- Performance and scalability
- Data access patterns

### 3. Design Business Continuity Solutions — 15–20%

Study:

- High availability
- Disaster recovery
- Azure Backup
- Azure Site Recovery
- Recovery objectives
- RPO and RTO
- Availability Zones
- Regional resilience
- Backup architecture
- Recovery testing
- Business continuity planning

### 4. Design Infrastructure Solutions — 30–35%

Study:

- Azure virtual networks
- Network security
- VPN and ExpressRoute
- Load balancing
- Application Gateway
- Azure Front Door
- Azure Firewall
- Private Link
- DNS
- Virtual machines
- VM Scale Sets
- Containers
- Azure App Service
- AKS
- Infrastructure migration
- Hybrid architecture

## Detailed Study Notes

### Azure Architecture

Start with business requirements before selecting services. Evaluate security, reliability, performance efficiency, operational excellence, cost optimization, and sustainability using the **Azure Well-Architected Framework**.

The **Cloud Adoption Framework for Azure** helps organize cloud adoption, governance, landing zones, and operating models.

### Identity and Governance

Understand the difference between authentication, authorization, RBAC, managed identities, and policy.

**Example:** A workload that needs access to Azure Storage should preferably use a managed identity rather than embedding long-lived credentials in application code.

### Azure Networking

Study virtual networks, subnets, NSGs, routing, VPN Gateway, ExpressRoute, Private Link, Azure Firewall, Application Gateway, Front Door, and DNS.

When designing a network, consider traffic direction, segmentation, private connectivity, security boundaries, availability, and hybrid requirements.

### Storage

Choose storage according to workload requirements.

Consider:

- Object vs file vs disk storage
- Performance
- Redundancy
- Access patterns
- Security
- Data lifecycle
- Availability
- Cost

### Business Continuity

Understand **RPO** and **RTO**.

- **RPO:** Maximum acceptable amount of data loss measured in time.
- **RTO:** Maximum acceptable time to restore service.

Select backup, replication, availability zones, or regional recovery based on business requirements rather than using the same design for every workload.

### Compute

Understand when to use:

- Virtual Machines
- VM Scale Sets
- App Service
- Containers
- Azure Kubernetes Service

Compare control, scalability, management overhead, deployment model, and application requirements.

### Monitoring

Azure Monitor provides a broad monitoring platform. Study metrics, logs, Log Analytics, Application Insights, alerts, dashboards, and diagnostic settings.

Architecture decisions should ensure that critical workloads provide sufficient observability for operations and troubleshooting.

## Important Concepts

- Microsoft Entra ID
- Azure RBAC
- Managed identities
- Azure Policy
- Management groups
- Azure Monitor
- Log Analytics
- Application Insights
- Azure Storage
- Azure SQL
- Cosmos DB
- RPO and RTO
- Azure Backup
- Azure Site Recovery
- Availability Zones
- Virtual Networks
- VPN Gateway
- ExpressRoute
- Private Link
- Azure Firewall
- Application Gateway
- Azure Front Door
- VM Scale Sets
- App Service
- Containers
- AKS
- Well-Architected Framework
- Cloud Adoption Framework

## Practical Examples / Labs

Use Microsoft Learn sandboxes, Azure free/trial resources, or authorized subscriptions.

1. Design a hub-and-spoke Azure network.
2. Configure VNets, subnets, NSGs, and route tables.
3. Compare VPN Gateway and ExpressRoute architectures.
4. Configure a private endpoint for an Azure service.
5. Create an Azure RBAC design using least privilege.
6. Deploy a workload using a managed identity.
7. Configure Azure Monitor and Log Analytics.
8. Design a highly available VM architecture.
9. Compare App Service, containers, and AKS for a sample application.
10. Configure Azure Storage redundancy and security.
11. Create a backup and disaster-recovery architecture.
12. Calculate appropriate RPO and RTO requirements for sample workloads.
13. Design a hybrid Azure connectivity solution.
14. Evaluate an architecture using the Well-Architected Framework.

Never test against cloud resources or systems without authorization.

## Study Strategy

Start with Microsoft's official AZ-305 Study Guide and allocate time according to the domain percentages.

Focus on **architecture decisions**, not memorizing service descriptions. For each scenario, identify:

1. Business requirements
2. Technical constraints
3. Security requirements
4. Availability requirements
5. Performance requirements
6. Cost considerations
7. Operational requirements

Then select the Azure architecture that best satisfies those constraints.

Combine Microsoft Learn theory, architecture diagrams, hands-on Azure labs, scenario analysis, and Microsoft's official Practice Assessment.

Avoid exam dumps, leaked questions, and recalled-question collections.

## 30-Day Study Plan

| Days | Focus |
|---|---|
| 1–4 | Entra ID, RBAC, managed identities, governance |
| 5–7 | Azure Policy, management groups, monitoring |
| 8–12 | Storage, Azure SQL, Cosmos DB, data architecture |
| 13–16 | Backup, Site Recovery, RPO/RTO, high availability |
| 17–21 | VNets, routing, VPN, ExpressRoute, Private Link |
| 22–25 | Firewall, Application Gateway, Front Door, DNS |
| 26–27 | VM, VMSS, App Service, containers, AKS |
| 28 | Hybrid architecture + Well-Architected Framework |
| 29 | Official Practice Assessment + weak areas |
| 30 | Full architecture review and exam readiness |

## Common Mistakes

- Choosing an Azure service before identifying the requirement.
- Confusing authentication with authorization.
- Ignoring least privilege.
- Choosing redundancy without considering RPO/RTO.
- Confusing VPN Gateway with ExpressRoute.
- Ignoring private connectivity requirements.
- Selecting AKS when a simpler managed platform is sufficient.
- Focusing only on technology while ignoring cost and operations.
- Memorizing product features without understanding architecture.
- Using exam dumps instead of legitimate resources.

## Exam-Day Tips

- Read the complete scenario before selecting an answer.
- Identify the business requirement first.
- Watch for words such as **minimum cost**, **minimum administrative effort**, **highest availability**, **least privilege**, and **lowest latency**.
- Eliminate services that do not satisfy the stated constraints.
- Compare similar Azure services carefully.
- For disaster recovery questions, identify the required RPO and RTO.
- For networking questions, trace the complete traffic path.
- Manage the 100-minute exam carefully.

## Final Checklist

- [ ] Reviewed all four AZ-305 domains
- [ ] Understand Entra ID and Azure RBAC
- [ ] Reviewed governance and Azure Policy
- [ ] Understand Azure Monitor
- [ ] Reviewed storage and database architectures
- [ ] Understand RPO/RTO and disaster recovery
- [ ] Practiced Azure networking
- [ ] Reviewed VPN, ExpressRoute, Private Link, and Firewall
- [ ] Understand compute service selection
- [ ] Reviewed Well-Architected Framework
- [ ] Reviewed Cloud Adoption Framework
- [ ] Completed official practice resources
- [ ] Verified the latest Microsoft Learn objectives

## Official Resources

- AZ-305 Exam: https://learn.microsoft.com/en-us/credentials/certifications/exams/az-305/
- AZ-305 Study Guide: https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-305
- Azure Solutions Architect Expert: https://learn.microsoft.com/en-us/credentials/certifications/azure-solutions-architect/
- Azure Architecture Center: https://learn.microsoft.com/en-us/azure/architecture/
- Azure Well-Architected Framework: https://learn.microsoft.com/en-us/azure/well-architected/
- Cloud Adoption Framework: https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/
- Microsoft Learn Practice Assessments: https://learn.microsoft.com/en-us/credentials/certifications/practice-assessments-for-microsoft-certifications

## Voucher / Discount

Learn SecByte, an official Microsoft reseller partner, provides certification voucher options.

**Microsoft AZ-305 voucher:**

https://learn.secbyte.org/vouchers/microsoft-az-305

Learn SecByte's official Black Friday offer provides up to 70% off selected Microsoft exam vouchers.

Check the current offer and availability before purchasing. This does not mean that AZ-305 is specifically 70% off; verify the current promotion and eligibility with the provider.

## Disclaimer

This is an independent/community study guide and is not affiliated with or endorsed by Microsoft. Microsoft, Azure, Microsoft Entra, Azure Monitor, and related names are trademarks of Microsoft Corporation.

Exam objectives, certification requirements, pricing, languages, features, and availability may change. Candidates should verify current information with Microsoft before registering. Voucher pricing and availability may also change.

This repository contains educational material only and does **not** contain exam dumps, leaked questions, or recalled exam questions.
