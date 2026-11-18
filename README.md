# AWS Certified Solutions Architect – Associate (SAA-C03) Portfolio

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Certified%20Solutions%20Architect%20--%20Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS SAA-C03 Badge">
  <img src="https://img.shields.io/badge/Status-Passed%20(Nov%202026)-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Infrastructure-Terraform%20%2F%20AWS-blue?style=for-the-badge&logo=terraform" alt="Infrastructure">
</p>

Welcome to my central engineering repository for the **AWS Certified Solutions Architect – Associate (SAA-C03)** certification and accompanying cloud-native projects. 

This repository serves two purposes:
1. **Comprehensive Knowledge Base:** Structured, production-grade notes mapped directly to the 4 core domains of the SAA-C03 exam.
2. **Hands-On Project Lab:** Real-world implementations built using Infrastructure as Code (Terraform), serverless architectures, and AWS best practices (Well-Architected Framework).

---

## 🏗️ Repository Architecture

| Directory | Description | Target Audience / Use Case |
| :--- | :--- | :--- |
| [`/docs`](./docs) | Modularized exam notes broken down by SAA-C03 official domains. | Quick reference for AWS services, design patterns, and trade-offs. |
| [`/projects`](./projects) | Production-grade hands-on labs and architectural implementations. | Demonstrating real-world IaC, networking, and security competence. |
| [`/references`](./references) | Cleanly archived raw study logs, cheat sheets, and reference materials. | Deep archival background. |

---

## 📚 SAA-C03 Domain Notes

My notes focus heavily on **trade-offs**, cost constraints, and high-availability design patterns rather than superficial definitions:

- **[Domain 1: Resilient Architectures](./docs/01-resilient-architectures/)** — Multi-AZ/Multi-Region setups, Auto Scaling strategies, disaster recovery (RTO/RPO), and decoupled messaging (SQS, SNS).
- **[Domain 2: High-Performing Architectures](./docs/02-high-performing-architectures/)** — High-performance computing (HPC), caching layers (ElastiCache, DynamoDB Accelerator), database scaling (Aurora, RDS Read Replicas), and edge delivery (CloudFront).
- **[Domain 3: Secure Applications and Architectures](./docs/03-secure-architectures/)** — IAM least-privilege, KMS key policies, VPC security (NACLs vs. Security Groups), WAF, Shield, and GuardDuty.
- **[Domain 4: Cost-Optimized Architectures](./docs/04-cost-optimized-architectures/)** — Storage tiering (S3 lifecycle policies), EC2 pricing models (Spot, Reserved, Savings Plans), and cost visibility (AWS Budgets, Cost Explorer).

---

## 🚀 Hands-On Project Roadmap

| # | Project Name | Key Technologies | Status |
|:-:|:---|:---|:---:|
| 1 | **Production-Grade Multi-Tier VPC** | Terraform, VPC, NAT Gateways, ALB, Private Subnets | 🚧 In Progress |
| 2 | **Serverless Event-Driven Order Pipeline** | AWS Lambda, API Gateway, SQS, DynamoDB, SNS | 📅 Planned |
| 3 | **Disaster Recovery Multi-Region Warm Standby** | Route 53, Aurora Global Databases, S3 Replication | 📅 Planned |

---

## 🛠️ Local Development & Standards

All infrastructure code inside `/projects` follows clean coding standards:
* **Terraform:** Formatted with `terraform fmt`, validated with `terraform validate`, and checked via `tflint`.
* **Documentation:** Written in GitHub Flavored Markdown with clear ASCII or Mermaid architecture diagrams.

---

## 📄 License

Distributed under the [MIT License](./LICENSE). Feel free to reference these notes or projects for your own cloud engineering journey!