<div align="center">

### Amir Nurhakim
<sub>**DevOps Engineer** @ [Silentmode](https://www.silentmode.my/) | **CS (Multimedia) Graduate** @ [UPM](https://www.upm.edu.my/)</sub>

*I run the cloud behind RONPOS and Sentinel.*

**5 production environments · 2,500+ stations**
<sub>Shell MY · Shell SG · BHP · Petronas · Xcel and Five (in pilot)</sub>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrnrhkm-0A66C2?style=flat&logo=linkedin&logoSize=auto)](https://www.linkedin.com/in/mrnrhkm/)
[![GitHub](https://img.shields.io/badge/GitHub-amirrhkm-181717?style=flat&logo=github)](https://github.com/amirrhkm)
![Timezone](https://img.shields.io/badge/Timezone-MYT-FF6B6B?style=flat)

</div>

## What I run

- **RONPOS**: Shell MY, Shell SG, BHP, Xcel, Five
- **Sentinel**: Petronas

The whole cloud estate: the back-office and head-office platforms (CloudBOS, HOS), the MQTT pipeline from on-prem sites, and every third-party integration, from SFTP report hand-offs to forecourt sales files landing straight in the cloud.

I build and maintain the production pipelines, and when production breaks I'm the one who resolves it, because I know every environment end to end. Seen and fixed: database upgrades, silent data-path failures, gateway timeouts, full disks.

## Built end-to-end

- **Cryo**: one switch for non-prod. On-demand or scheduled on/off for EC2, ECS, RDS and EventBridge across 3 UAT environments. **~50% off non-prod cloud cost.**
- **[Qualys scan automation](https://github.com/amirrhkm/qualys-scanpipe)**: network scans run inside the production pipeline, driven by SQS FIFO and a Step Functions state machine, with status emails, ASV report and attestation, and remediation-SLA tracking. **Zero manual scans.**
- **KPMG integration**: EventBridge, a Lambda producer, SQS, auto-scaling ECS Fargate workers, S3, then least-privilege SFTP for the third party to collect.
- **[TEAM (fork)](https://github.com/amirrhkm/team-platform)**: short-lived, audited AWS access for engineers, extended with cross-region IDC and app support.

<details>
<summary>Stack</summary>

| | |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white) |
| **Cloud / IaC** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white) ![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat&logo=serverless&logoColor=white) |
| **Observability** | ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat&logo=amazon-aws&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) |
| **CI/CD** | ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white) |
| **Data** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazon-dynamodb&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white) |
| **Security** | ![GuardDuty](https://img.shields.io/badge/GuardDuty-DD344C?style=flat&logo=amazon-aws&logoColor=white) ![WAF](https://img.shields.io/badge/WAF-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat&logo=sonarqube&logoColor=white) ![Qualys](https://img.shields.io/badge/Qualys-660066?style=flat) |

</details>

<div align="center">
<sub>Off the clock: F1 and go-karts, where the only thing I'm trying to keep up is lap time.</sub>

<sub>Jack of all trades, master of none, but often times better than master of one.</sub>
</div>
