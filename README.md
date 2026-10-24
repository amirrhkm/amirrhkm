<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Amir Nurhakim, DevOps Engineer @ Silentmode. I run the cloud behind RONPOS and Sentinel." src="assets/banner-light.svg" width="900">
</picture>

<sub>**DevOps Engineer** @ [Silentmode](https://www.silentmode.my/) &nbsp;·&nbsp; **CS (Multimedia) Graduate** @ [UPM](https://www.upm.edu.my/)</sub>

![Production environments](https://img.shields.io/badge/PRODUCTION_ENVS-5-0A66C2?style=for-the-badge)
![Stations](https://img.shields.io/badge/STATIONS-2%2C500%2B-7B42BC?style=for-the-badge)
![UAT cost saved](https://img.shields.io/badge/UAT_COST_SAVED-~50%25-2EA043?style=for-the-badge)

<sub>Shell MY · Shell SG · BHP · Petronas · Xcel and Five (in pilot)</sub>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrnrhkm-0A66C2?style=flat&logo=linkedin&logoSize=auto)](https://www.linkedin.com/in/mrnrhkm/)
[![GitHub](https://img.shields.io/badge/GitHub-amirrhkm-181717?style=flat&logo=github)](https://github.com/amirrhkm)
![Timezone](https://img.shields.io/badge/Timezone-MYT-FF6B6B?style=flat)

</div>

## ☁️ What I run

| Product | Clients |
|---|---|
| **RONPOS** | Shell MY · Shell SG · BHP · Xcel · Five |
| **Sentinel** | Petronas |

The whole cloud estate: the back-office and head-office platforms (CloudBOS, HOS), the MQTT pipeline from on-prem sites, and every third-party integration, from SFTP report hand-offs to forecourt sales files landing straight in the cloud.

> [!NOTE]
> I build and maintain the production pipelines, and when production breaks I'm the one who resolves it, because I know every environment end to end. Seen and fixed: database upgrades, silent data-path failures, gateway timeouts, full disks.

## 🛠️ Built end-to-end

| Project | What it does | Result |
|---|---|---|
| **Cryo** | One switch for non-prod. On-demand or scheduled on/off for EC2, ECS, RDS and EventBridge across 3 UAT environments. | **~50% off** non-prod cloud cost |
| **[Qualys scan automation](https://github.com/amirrhkm/qualys-scanpipe)** | Network scans run inside the production pipeline, driven by SQS FIFO and a Step Functions state machine, with status emails, ASV report and attestation, and remediation-SLA tracking. | **Zero** manual scans |
| **KPMG integration** | EventBridge, a Lambda producer, SQS, auto-scaling ECS Fargate workers, S3, then least-privilege SFTP for the third party to collect. | Hands-off daily delivery |
| **[TEAM (fork)](https://github.com/amirrhkm/team-platform)** | Short-lived, audited AWS access for engineers, extended with cross-region IDC and app support. | Time-boxed access, full audit trail |

## 🧰 Stack

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

<div align="center">
<sub>Jack of all trades, master of none, but often times better than master of one.</sub>
</div>
