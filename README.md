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

## ☁️ What I run at Silentmode

| Product | Clients |
|---|---|
| **RONPOS** | Shell MY · Shell SG · BHP · XCel · FIVE |
| **Sentinel** | Petronas |

The whole cloud estate: the back-office and head-office platforms (CloudBOS, HOS), the MQTT pipeline from on-prem sites, and every third-party integration, from SFTP report hand-offs to forecourt sales files landing straight in the cloud.

> [!NOTE]
> I build and maintain the production pipelines. When something breaks, I'm usually the person the team turns to, and I've worked through a long list of them across every environment.

<details>
<summary><b>Incidents I've worked through at Silentmode</b></summary>

<br>

- **Databases:** Aurora MySQL 5.7 → 8.0 upgrade regressions · connection exhaustion · deadlocks · long-running queries locking tables · tenant DB performance degradation · temp-table-full errors after a major upgrade
- **Search and storage:** OpenSearch out of disk · JVM memory pressure · silent bulk-insert failures that went unnoticed for weeks · unbounded index retention
- **Pipelines and queues:** Kinesis and SQS backlogs · delayed transaction processing · queue-worker out-of-memory · full disks · Lambda timeout and memory tuning
- **MQTT and station fleet:** broker CPU exhaustion · fuel price updates not reaching stations · fleet-wide cloud disconnects traced to a customer's network path · stale Redis connections in the socket workers · socket.io 404s found across multiple environments
- **Edge and network:** WAF Bot Control blocking legitimate traffic · gateway timeouts and 5xx on login and report pages · a security-hardening change that cut off internal connectivity
- **Third parties:** payment-authorization service outages · integration RPC timeouts · email delivery blocklisted by a mail provider · e-invoice submission failures
- **Platform:** GitLab runners hanging CI jobs · flaky end-to-end pipelines · a full AWS account migration cutover

</details>

<div align="center"><img src="assets/divider.svg" alt="" width="900"></div>

## 🛠️ Built end-to-end at Silentmode

| Project | What it does | Result |
|---|---|---|
| **Cryo** | One switch for non-prod. On-demand or scheduled on/off for EC2, ECS, RDS and EventBridge across 3 UAT environments. | **~50% off** non-prod cloud cost |
| **[Qualys scan automation](https://github.com/amirrhkm/qualys-scanpipe)** | Network scans run inside the production pipeline, driven by SQS FIFO and a Step Functions state machine, with status emails, ASV report and attestation, and remediation-SLA tracking. | **Zero** manual scans |
| **KPMG integration** | EventBridge, a Lambda producer, SQS, auto-scaling ECS Fargate workers, S3, then least-privilege SFTP for the third party to collect. | Hands-off daily delivery |
| **[TEAM (fork)](https://github.com/amirrhkm/team-platform)** | Short-lived, audited AWS access for engineers, extended with cross-region IDC and app support. | Time-boxed access, full audit trail |

<div align="center"><img src="assets/divider.svg" alt="" width="900"></div>

## 🧰 Stack

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <img alt="Tech stack map: languages, frameworks, CI/CD, containers and tools, cloud and IaC, network, data, observability, security" src="assets/stack-light.svg" width="900">
</picture>
</div>

<details>
<summary>Same stack, with logos</summary>

<br>

| | |
|---|---|
| **Programming Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Cloud Provider** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) |
| **IaC** | ![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat&logo=serverless&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white) |
| **Framework** | ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white) |
| **Observability** | ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat&logo=amazon-aws&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white) ![DataPrepper](https://img.shields.io/badge/DataPrepper-232F3E?style=flat&logo=dataprepper&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![rsyslog](https://img.shields.io/badge/rsyslog-EE0000?style=flat&logo=linux&logoColor=white) |
| **CI/CD** | ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white) |
| **Tools** | ![steampipe](https://img.shields.io/badge/steampipe-000000?style=flat&logoColor=white) ![kops](https://img.shields.io/badge/kops-326CE5?style=flat&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white) ![kubectl](https://img.shields.io/badge/kubectl-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-326CE5?style=flat&logo=docker&logoColor=white) ![TablePlus](https://img.shields.io/badge/TablePlus-FF9900?style=flat&logo=tableplus&logoColor=white) ![ansible](https://img.shields.io/badge/Ansible-000000?style=flat&logo=ansible&logoColor=white) ![systemd](https://img.shields.io/badge/systemd-0078D4?style=flat&logo=linux&logoColor=white) |
| **Network Protocols** | ![HTTP](https://img.shields.io/badge/HTTP-005C84?style=flat) ![TLS](https://img.shields.io/badge/TLS-721412?style=flat) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat) ![SSH](https://img.shields.io/badge/SSH-4D4D4D?style=flat) ![SFTP](https://img.shields.io/badge/SFTP-0078D4?style=flat) ![gRPC](https://img.shields.io/badge/gRPC-EE0000?style=flat&logo=gRPC&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazon-dynamodb&logoColor=white) ![ElastiCache](https://img.shields.io/badge/ElastiCache-C925D1?style=flat&logo=redis&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white) |
| **Security** | ![GuardDuty](https://img.shields.io/badge/GuardDuty-DD344C?style=flat&logo=amazon-aws&logoColor=white) ![WAF](https://img.shields.io/badge/WAF-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat&logo=sonarqube&logoColor=white) ![Qualys](https://img.shields.io/badge/Qualys-660066?style=flat) |

</details>

<div align="center">
<sub>Jack of all trades, master of none, but often times better than master of one.</sub>
</div>
