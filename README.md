<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Amir Nurhakim, DevOps Engineer at Silentmode. I run the cloud behind RONPOS and Sentinel." src="assets/banner-light.svg" width="900">
</picture>

<sub>**DevOps Engineer** @ [Silentmode](https://www.silentmode.my/) &nbsp;·&nbsp; **CS (Multimedia) Graduate** @ [UPM](https://www.upm.edu.my/)</sub>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img alt="5 production environments, 2,500+ stations served, about 50% non-prod cost saved" src="assets/stats-light.svg" width="900">
</picture>

<sub>Shell MY · Shell SG · BHP · Petronas · XCel · FIVE</sub>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrnrhkm-0A66C2?style=flat&logo=linkedin&logoSize=auto)](https://www.linkedin.com/in/mrnrhkm/)
[![GitHub](https://img.shields.io/badge/GitHub-amirrhkm-181717?style=flat&logo=github)](https://github.com/amirrhkm)
![Timezone](https://img.shields.io/badge/Timezone-MYT-FF6B6B?style=flat)

<img src="assets/divider.svg" alt="" width="900">

</div>

## Infrastructure

The whole cloud estate: the back-office and head-office platforms (CloudBOS, HOS), the MQTT pipeline from on-prem sites, and every third-party integration, from SFTP report hand-offs to forecourt sales files landing straight in the cloud.

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/infra-dark.svg">
  <img alt="Infrastructure map. Security and compliance: secrets and AWS access, least-privilege roles for TEAM, WAF and AWS security services, audit evidence for PCI-DSS, SOC 2 and ISO 27001. Delivery: GitLab access, pipelines and runners; SonarQube set up before a service deploys; Qualys network scans in the pipeline. Operations: monitoring and alerts with CloudWatch and Sentry; Mailgun email delivery; MQTT and third-party integrations. Cloud foundation: AWS in every environment, new environments and service onboarding as code, backup and restore for databases and GitLab, cost governance including stale resources and technical debt." src="assets/infra-light.svg" width="900">
</picture>
</div>

> [!NOTE]
> I build and maintain the production pipelines. When something breaks, I'm usually the person the team turns to, and I've worked through a long list of them across every environment.

<details>
<summary><b>Incidents I've worked through</b></summary>

<br>

- **Databases:** Aurora MySQL 5.7 → 8.0 upgrade regressions · connection exhaustion · deadlocks · long-running queries locking tables · tenant DB performance degradation · temp-table-full errors after a major upgrade
- **Search and storage:** OpenSearch out of disk · JVM memory pressure · silent bulk-insert failures that went unnoticed for weeks · unbounded index retention
- **Pipelines and queues:** Kinesis and SQS backlogs · delayed transaction processing · queue-worker out-of-memory · full disks · Lambda timeout and memory tuning
- **MQTT and station fleet:** broker CPU exhaustion · fuel price updates not reaching stations · fleet-wide cloud disconnects traced to a customer's network path · stale Redis connections in the socket workers · socket.io 404s found across multiple environments
- **Edge and network:** WAF Bot Control blocking legitimate traffic · gateway timeouts and 5xx on login and report pages · a security-hardening change that cut off internal connectivity
- **Third parties:** payment-authorization service outages · integration RPC timeouts · email delivery blocklisted by a mail provider · e-invoice submission failures
- **Platform:** GitLab runners hanging CI jobs · flaky end-to-end pipelines · a full AWS account migration cutover
- **Follow-up:** RCA write-ups

</details>

<div align="center"><img src="assets/divider.svg" alt="" width="900"></div>

## Projects

<div align="center">
<img alt="Terminal output of kubectl get projects: cryo (EC2, ECS, RDS and EventBridge scheduler, ~50% off non-prod cost), qualys-scanpipe (SQS FIFO and Step Functions, zero manual scans), kpmg-integration (EventBridge, SQS, Fargate, S3, SFTP, hands-off daily delivery), team fork (Amplify app for short-lived, audited AWS access). A selection, not the full list." src="assets/projects-terminal.svg" width="900">

<sub>Source: [qualys-scanpipe](https://github.com/amirrhkm/qualys-scanpipe) · [team-platform](https://github.com/amirrhkm/team-platform)</sub>
</div>

<div align="center"><img src="assets/divider.svg" alt="" width="900"></div>

## Stack

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <img alt="Tech stack map: languages, frameworks, CI/CD, containers and tools, cloud and IaC, network, data, observability, security" src="assets/stack-light.svg" width="900">
</picture>
</div>

## Goals

- [ ] **AWS Certified Solutions Architect – Associate** (SAA-C03)

<div align="center">
<sub>Jack of all trades, master of none, but often times better than master of one.</sub>
</div>
