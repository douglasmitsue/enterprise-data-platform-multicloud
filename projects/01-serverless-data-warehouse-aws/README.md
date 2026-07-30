# Serverless Data Warehouse on AWS

![AWS](https://img.shields.io/badge/AWS-Serverless-orange)
![Terraform](https://img.shields.io/badge/Terraform-IaC-blue)
![Glue](https://img.shields.io/badge/AWS-Glue-yellow)
![Athena](https://img.shields.io/badge/AWS-Athena-purple)
![Lake Formation](https://img.shields.io/badge/Data-Lakehouse-green)

This project demonstrates how to build a fully serverless Data Warehouse on AWS using managed services, following the principles of the Modern Data Stack and the Lakehouse architecture.

---

## Objectives

The goal of this project is to demonstrate, in practice, how to build an analytics platform using AWS managed services.

Throughout this project, the following concepts will be covered:

- Data Lake
- Data Warehouse
- ETL
- ELT
- Data Lakehouse
- Data Catalog
- Data Governance
- Security
- Infrastructure as Code (IaC)
- Architecture Best Practices

---

## Architecture

![Architecture](images/architecture.png)

---

## Technologies

- Amazon S3
- AWS Glue
- AWS Athena
- AWS Lake Formation
- AWS IAM
- AWS Lambda
- Amazon EventBridge
- AWS Step Functions
- AWS CloudWatch
- Terraform

---

## Overall Architecture

```text
Data Source
      │
      ▼
Amazon S3 (Raw)
      │
      ▼
AWS Glue ETL
      │
      ▼
Amazon S3 (Curated)
      │
      ▼
AWS Glue Data Catalog
      │
      ▼
Amazon Athena
      │
      ▼
Power BI
```

---

## Project Structure

```text
serverless-data-warehouse-aws
│
├── architecture
├── terraform
├── glue
├── lambda
├── athena
├── docs
└── images
```

---

## AWS Services Used

| Service | Purpose |
|----------|---------|
| Amazon S3 | Data Lake |
| AWS Glue | ETL |
| Amazon Athena | SQL Analytics |
| AWS Lake Formation | Data Governance |
| AWS IAM | Security |
| AWS Lambda | Automation |
| Amazon EventBridge | Scheduling |
| AWS Step Functions | Workflow Orchestration |
| Amazon CloudWatch | Monitoring |

---

## Roadmap

- [ ] Create the Data Lake
- [ ] Configure IAM
- [ ] Create the Bronze Bucket
- [ ] Create the Silver Bucket
- [ ] Create the Gold Bucket
- [ ] Configure the AWS Glue Data Catalog
- [ ] Create AWS Glue Crawlers
- [ ] Develop AWS Glue ETL Jobs
- [ ] Create Amazon Athena Queries
- [ ] Build Power BI Dashboards
- [ ] Automate the Data Pipeline
- [ ] Implement Monitoring
- [ ] Write Project Documentation

---

## Learning Outcomes

Throughout this project, the following concepts will be explored:

- Data Lake
- Medallion Architecture
- ETL vs. ELT
- Lakehouse
- Serverless Analytics
- Data Governance
- Data Quality
- Infrastructure as Code (IaC)

---

## References

- AWS Documentation
- AWS Well-Architected Framework
- AWS Analytics Reference Architecture

---

## Author

**Douglas Mitsue**

**Data Architect | Azure | AWS | Modern Data Stack**