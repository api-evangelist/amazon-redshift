# Amazon Redshift (amazon-redshift)
Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-redshift/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Big Data, Cloud, Data Lake, Data Warehouse, ETL, Machine Learning, Serverless, SQL

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Amazon Redshift API
The Amazon Redshift API for managing clusters, snapshots, and configurations.

**Human URL:** [https://aws.amazon.com/redshift/](https://aws.amazon.com/redshift/)

#### Tags:

 - Clusters, Data Warehouse, Snapshots

#### Properties

- [Documentation](https://docs.aws.amazon.com/redshift/)
- [OpenAPI](https://api.apis.guru/v2/specs/amazonaws.com/redshift/2012-12-01/openapi.yaml)
- [APIReference](https://docs.aws.amazon.com/redshift/latest/APIReference/Welcome.html)
- [GettingStarted](https://docs.aws.amazon.com/redshift/latest/gsg/getting-started.html)
- [Pricing](https://aws.amazon.com/redshift/pricing/)
- [Console](https://console.aws.amazon.com/redshift/)
- [SDK - Python SDK](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift.html)
- [SDK - JavaScript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/client/redshift/)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/redshift/)
- [BestPractices](https://docs.aws.amazon.com/redshift/latest/dg/best-practices.html)
- [Security](https://docs.aws.amazon.com/redshift/latest/mgmt/security.html)
- [FAQ](https://aws.amazon.com/redshift/faqs/)
- [ReleaseNotes](https://docs.aws.amazon.com/redshift/latest/mgmt/cluster-versions.html)
- [ChangeLog](https://docs.aws.amazon.com/redshift/latest/mgmt/document-history.html)

### Amazon Redshift Data API
The Amazon Redshift Data API for running SQL statements without managing connections. Supports asynchronous execution with IAM and Secrets Manager authentication.

**Human URL:** [https://docs.aws.amazon.com/redshift/latest/mgmt/data-api.html](https://docs.aws.amazon.com/redshift/latest/mgmt/data-api.html)

#### Tags:

 - Data API, Serverless, SQL

#### Properties

- [Documentation](https://docs.aws.amazon.com/redshift/latest/mgmt/data-api.html)
- [APIReference](https://docs.aws.amazon.com/redshift-data/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-redshift-data-api-openapi.yml)
- [SDK - Python SDK](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-data.html)
- [SDK - JavaScript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/client/redshift-data/)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/redshift-data/)
- [GettingStarted](https://aws.amazon.com/blogs/big-data/get-started-with-the-amazon-redshift-data-api/)

### Amazon Redshift Serverless API
The Amazon Redshift Serverless API for managing serverless data warehouse workgroups, namespaces, and capacity without provisioning clusters.

**Human URL:** [https://docs.aws.amazon.com/redshift/latest/mgmt/serverless-whatis.html](https://docs.aws.amazon.com/redshift/latest/mgmt/serverless-whatis.html)

#### Tags:

 - Data Warehouse, Namespaces, Serverless, Workgroups

#### Properties

- [Documentation](https://docs.aws.amazon.com/redshift/latest/mgmt/working-with-serverless.html)
- [APIReference](https://docs.aws.amazon.com/redshift-serverless/latest/APIReference/Welcome.html)
- [SDK - Python SDK](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift-serverless.html)
- [SDK - JavaScript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/client/redshift-serverless/)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/redshift-serverless/)
- [GettingStarted](https://docs.aws.amazon.com/redshift/latest/mgmt/serverless-whatis.html)
- [Pricing](https://aws.amazon.com/redshift/pricing/)

## Common Properties

- [Blog](https://aws.amazon.com/blogs/big-data/category/database/amazon-redshift/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Documentation](https://docs.aws.amazon.com/redshift/)
- [GettingStarted](https://aws.amazon.com/redshift/getting-started/)
- [FAQ](https://aws.amazon.com/redshift/faqs/)
- [Pricing](https://aws.amazon.com/redshift/pricing/)
- [Console](https://console.aws.amazon.com/redshift/)
- [StatusPage](https://status.aws.amazon.com/)

## Features

| Name | Description |
|------|-------------|
| Massively Parallel Processing | Distributed query execution across multiple nodes for petabyte-scale analytics with sub-second response times. |
| Serverless Data Warehouse | Auto-scaling compute capacity without cluster provisioning, paying only for compute used during queries. |
| Data API | Run SQL statements without managing database connections using IAM-based authentication and asynchronous execution. |
| Federated Query | Query data across Amazon RDS, Aurora, and S3 data lakes without moving data using federated query capabilities. |
| Machine Learning Integration | Build, train, and deploy ML models directly in Redshift using SQL with Amazon SageMaker integration. |
| Concurrency Scaling | Automatically add transient capacity to handle bursts of concurrent queries without performance degradation. |

## Use Cases

| Name | Description |
|------|-------------|
| Business Intelligence Analytics | Run complex analytical queries across petabytes of structured data for BI dashboards and reporting. |
| Data Lake Analytics | Query data directly in Amazon S3 using Redshift Spectrum without loading it into the warehouse. |
| Real-Time Analytics | Ingest streaming data and run near-real-time analytics on operational data for instant insights. |
| ETL Pipeline Processing | Transform and load large datasets using SQL-based ETL operations within the data warehouse. |
| Serverless Ad-Hoc Queries | Run on-demand analytical queries without provisioning clusters using Redshift Serverless and Data API. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Load data from and query data in S3 using COPY commands, Redshift Spectrum, and data lake integration. |
| AWS Glue | Automated ETL job orchestration and data catalog integration for data warehouse loading. |
| Amazon QuickSight | Connect QuickSight directly to Redshift for serverless BI dashboards and visualizations. |
| AWS Lambda | Trigger Lambda functions from Redshift Data API results for event-driven data processing workflows. |
| Terraform | Provision and manage Redshift clusters and serverless workgroups using Terraform infrastructure-as-code. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Redshift Data API](openapi/amazon-redshift-data-api-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Redshift Data API](capabilities/shared/redshift-data.yaml) -- 10 operations for SQL execution and metadata

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Warehouse Analytics](capabilities/data-warehouse-analytics.yaml) | Redshift Data API | 10 | Data Analyst / Data Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
