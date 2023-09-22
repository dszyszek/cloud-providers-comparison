# Cloud providers comparison

## Table of content

1. [Factors](#factors)
2. [Vendors](#vendors)
3. [Services](#services-compared)
4. [Cost](#cost)
5. [Free tier comparison](#free-tier-comparison)
6. [Market share](#market-share)
7. [Support plans](#support-plans)
   - [AWS](#aws)
   - [Azure](#azure)
   - [GCP](#gcp)
8. [Managed services](#managed-services)
   - [AWS](#aws-1)
   - [Azure](#azure-1)
   - [GCP](#gcp-1)
9. [Bibliography](#bibliography)

## Factors

- services provided
- cost
- free tier options
- market share
- support plans
- infrastructure management
- managed services

## Vendors

- AWS
- Microsoft Azure
- GCP

## Services compared

You can find detailed services information with mapping to each platform [under that link](https://www.techtarget.com/searchcloudcomputing/feature/A-cloud-services-cheat-sheet-for-AWS-Azure-and-Google-Cloud) (pasting the link as there's no point of copy-pasting content to that document)

## Cost

Every of the 3 providers offers different pricing models depeding on user needs.
AWS offers pay-as-you go model with various usage calculation metrics. AWS cost calculation process is sophisticated enough you can find youself looking for 3rd party app to estimate cost of your infrastructure.
Azure and GCP offers pay-as-you-go along with pre-purchase models (commited use with a significant discount).

In general it's really hard to tell off the top of the head which cloud provider will be most suitable for any arbitrary system - it needs to be depely analysed. The simple heurystics would be:

- if organizations needs a deep feature portfolio, it can opt for AWS cloud services
- if organizations is seeking optimal innovation and low cost, GCP could be the best option
- if organization is primarily operating on Microsoft products, Azure is the best choice

Below you can find cost-wise comparison in between GCP, Azure and AWS

| Detail                     | Amazon AWS                                                                       | Microsoft Azure                                                      | Google GCP                                                                                                                                    |
| :------------------------- | :------------------------------------------------------------------------------- | :------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------- |
| Minimum Instance           | 2 virtual CPUs, and 8 GB of Ram will price you around – USD 69/month             | 2 virtual CPUs, and 8 GB of Ram will price you around – USD 70/month | 2 virtual CPUs, and 8 GB of Ram will price you around – USD 52/month                                                                          |
| Maximum Instance           | 3.84 TB Ram, 128 vCPUs will price you around – USD 3.97/hour                     | 3.89 TB Ram, 128 v CPUs will price you around – USD 6.97/hour        | 3.75 TB Ram, 160 v CPUs will price you around – USD 5.32/hour                                                                                 |
| Type of Discount           | Reserved Instances (RIs)                                                         | Reserved Instances (RIs)                                             | Committed Use Discount (CUD) <br /> Sustained Use Discount (SUD)                                                                              |
| Commitment                 | 1 or 3 years                                                                     | 1 or 3 years                                                         | Committed Use Discount (CUD) – 1 or 3 years <br /> Sustained Use Discount (SUD) – no commitment                                               |
| Discount percentage        | Up to 75 percent                                                                 | Up to 72 percent                                                     | Committed Use Discount (CUD) – for 1 year up to 37 percent or 3 years up to 55 percent <br /> Sustained Use Discount (SUD) – up to 30 percent |
| Is cancellation available? | Yes, it offers to sell your products on the marketplace                          | Yes, they will charge a 12% cancellation fee                         | No cancellation is available                                                                                                                  |
| Payment options            | 3 options are available on AWS – no up-front, partial up-front, all up-front     | All up-front                                                         | No up-front                                                                                                                                   |
| High Profile Customers     | LinkedIn, Facebook, BBC, Airbnb, Twitch, Netflix, Adobe, ESPN, Lamborghini, etc. | Apple, HP, Coca-Cola, LG Electronics, Verizon, Xbox, Fujifilm, etc.  | Twitter, Intel, Yahoo, PayPal, eBay, Target, 20th Century Fox, etc.                                                                           |

## Free tier comparison

| Type               | AWS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Azure                                                                                                                                                                                                                                                                                                                                                                                                            | GCP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 12-month free tier | <ul><li>Amazon EC2 Compute: 750 hours per month of compute time, per month of Linux, RHEL, SLES t2.micro or t3.micro instance and Windows t2.micro or t3.micro instance dependent on region</li><li>Amazon S3 Storage: 5GB of standard storage</li><li>Amazon RDS Database: 750 hours per month of db.t2.micro database usage using MySQL, PostgreSQL, MariaDB, Oracle BYOL, or SQL Server, 20 GB of General Purpose (SSD) database storage and 20 GB of storage for database backups and DB Snapshots</li></ul> | <ul><li>Linux and Windows virtual machines: 750 hours (using B1S VM) of compute time</li><li>Managed Disk Storage: 64 GB x 2 (P6 SSD)</li><li>Blob Storage: 5GB (LRS hot block)</li><li>File Storage: 5GB (LRS File Storage)</li><li>SQL databases: 250 GB</li></ul>                                                                                                                                             | None                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Always free        | <ul><li>AWS Lambda: 1 million free compute requests per month and up to 3.2 million seconds of compute time per month</li><li>Amazon DynamoDB: 25 GB of database storage per month, enough to handle up to 200M requests per month</li><li>Amazon CloudWatch: 10 custom metrics and alarms per month, 1,000,000 API requests, 5GB of Log Data Ingestion and Log Data Archive and 3 Dashboards with up to 50 metrics</li></ul>                                                                                    | <ul><li>Azure Kubernetes Service: no charge for cluster management, you only pay for the virtual machines and the associated storage and networking resources consumed</li><li>Azure DevOps: 5 users for open source projects and small projects (with unlimited private Git repos). For larger teams, the cost ranges from $6-$90 per month</li><li>Azure Cosmos DB (400 RU/s provisioned throughput)</li></ul> | <ul><li>Google BigQuery: 1 TB of queries and 10 GB of storage per month</li><li>Kubernetes Engine: One zonal cluster per month</li><li>Google Compute Engine: 1 f1-micro instance per month only in U.S. regions. 30 GB-months HDD, 5 GB-months snapshot in certain regions and 1 GB of outbound network data from North America to all region destinations per month</li><li>Google Cloud Storage: 5 GB of regional storage per month, only in the US. 5,000 Class A, and 50,000 Class B operations, and 1 GB of outbound network data from North America to all region destinations per month</li></ul> |

### Market share

According to Canalys, as of Q1 of 2023 the market share of 3 main cloud providers are:

![Cloud providers market share](https://canalys-prod-public.s3.eu-west-1.amazonaws.com/cosi/campaign/3309/nI42L~8UC7bnqTayhcXxMgnSzCCL2d3t.png)

But mind the fact the chart bases on the share in market value.
Below you can find another chart highlighting total amount of users + it's dynamics:

![Cloud providers amout of users](https://hginsights.com/wp-content/uploads/2023/03/gcp-report-blog-image-graph.jpg)

## Support plans

Below you can find most significant information about support options for each of the cloud vendors. Apart from the information in tables, under each of them you can find a link pointing directly to support plans webistes of each vendor.

### AWS

|              | Basic                                                                                                                                                               | Business                                                                                                                                                                                                                                       | Enterprise On-Ramp                                                                                                                                                                                                                   | Enterprise                                                                                                                                                                                                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Price        | Greater of: <ul><li>$29 / month</li><li>3% of monthly AWS usage</li></ul>                                                                                           | Greater of: <ul><li>$100 / month</li><li>10% of monthly AWS usage for the first $0–$10K <br/> 7% of monthly AWS usage from $10K–$80K <br /> 5% of monthly AWS usage from $80K–$250K <br /> 3% of monthly AWS usage over $250K <br /></li></ul> | Greater of: <ul><li>$5,500 / month</li><li>10% of monthly AWS usage</li></ul>                                                                                                                                                        | Greater of: <ul><li>$15,000 / month</li><li>10% of monthly AWS usage for the first $0–$150K <br /> 7% of monthly AWS usage from $150K–$500K <br /> 5% of monthly AWS usage from $500K–$1M <br /> 3% of monthly AWS usage over $1M </li></ul> |
| Support type | <ul><li>Business hours web access to Cloud Support Associates</li><li>Unlimited cases with 1 primary contact</li><li>Prioritized responses on AWS re:Post</li></ul> | <ul><li>24/7 phone, web, and chat access to Cloud Support Engineers</li><li>Unlimited cases and unlimited contacts (IAM supported)</li><li>Prioritized responses on AWS re:Post</li><li>Access to AWS Support App in Slack</li></ul>           | <ul><li>24/7 phone, web, and chat access to Cloud Support Engineers</li><li>Unlimited cases and unlimited contacts (IAM supported)</li><li>Prioritized responses on AWS re:Post</li><li>Access to AWS Support App in Slack</li></ul> | <ul><li>24/7 phone, web, and chat access to Cloud Support Engineers</li><li>Unlimited cases and unlimited contacts (IAM supported)</li><li>Prioritized responses on AWS re:Post</li><li>Access to AWS Support App in Slack</li></ul>         |
| Resonse time | <ul><li>General guidance: < 24 hours</li> <li>System impaired: < 12 hours</li> </ul>                                                                                | <ul><li>General guidance: < 24 hours</li> <li>System impaired: < 12 hours</li> <li>Production system impaired: < 4 hours</li><li>Production system down: < 1 hour</li></ul>                                                                    | <ul><li>General guidance: < 24 hours</li> <li>System impaired: < 12 hours</li> <li>Production system impaired: < 4 hours</li><li>Production system down: < 1 hour</li><li>Business-critical system down: < 30 minutes</li></ul>      | <ul><li>General guidance: < 24 hours</li> <li>System impaired: < 12 hours</li> <li>Production system impaired: < 4 hours</li><li>Production system down: < 1 hour</li><li>Business/Mission-critical system down: < 15 minutes</li></ul>      |

Detailed info ca be found [under the link](https://aws.amazon.com/premiumsupport/plans/)

### Azure

|              | Basic                                                                                                                                                                                                                              | Developer                                                                                                                                                                                                                                                                                                                                                                | Standard                                                                                                                                                                                                                                                                                                                                                                 | Professional Direct                                                                                                                                                                                                                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Price        | Included for all Azure customers                                                                                                                                                                                                   | $29 per month                                                                                                                                                                                                                                                                                                                                                            | $100 per month                                                                                                                                                                                                                                                                                                                                                           | $1,000 per month                                                                                                                                                                                                                                                                                                                                                         |
| Support type | <ul><li>24/7 SELF-HELP RESOURCES</li><li>ABILITY TO SUBMIT AS MANY SUPPORT TICKETS AS YOU NEED</li><li>AZURE ADVISOR—YOUR FREE, PERSONALIZED GUIDE TO AZURE BEST PRACTICES</li><li>AZURE HEALTH STATUS AND NOTIFICATIONS</li></ul> | <ul><li>24/7 SELF-HELP RESOURCES</li><li>ABILITY TO SUBMIT AS MANY SUPPORT TICKETS AS YOU NEED</li><li>AZURE ADVISOR—YOUR FREE, PERSONALIZED GUIDE TO AZURE BEST PRACTICES</li><li>AZURE HEALTH STATUS AND NOTIFICATIONS</li><li>THIRD-PARTY SOFTWARE SUPPORT</li><li>24/7 ACCESS TO TECHNICAL SUPPORT BY EMAIL AND PHONE AFTER A SUPPORT REQUEST IS SUBMITTED</li></ul> | <ul><li>24/7 SELF-HELP RESOURCES</li><li>ABILITY TO SUBMIT AS MANY SUPPORT TICKETS AS YOU NEED</li><li>AZURE ADVISOR—YOUR FREE, PERSONALIZED GUIDE TO AZURE BEST PRACTICES</li><li>AZURE HEALTH STATUS AND NOTIFICATIONS</li><li>THIRD-PARTY SOFTWARE SUPPORT</li><li>24/7 ACCESS TO TECHNICAL SUPPORT BY EMAIL AND PHONE AFTER A SUPPORT REQUEST IS SUBMITTED</li></ul> | <ul><li>24/7 SELF-HELP RESOURCES</li><li>ABILITY TO SUBMIT AS MANY SUPPORT TICKETS AS YOU NEED</li><li>AZURE ADVISOR—YOUR FREE, PERSONALIZED GUIDE TO AZURE BEST PRACTICES</li><li>AZURE HEALTH STATUS AND NOTIFICATIONS</li><li>THIRD-PARTY SOFTWARE SUPPORT</li><li>24/7 ACCESS TO TECHNICAL SUPPORT BY EMAIL AND PHONE AFTER A SUPPORT REQUEST IS SUBMITTED</li></ul> |
| Resonse time | N/A                                                                                                                                                                                                                                | Minimal business impact (Sev C): Within eight business hours1                                                                                                                                                                                                                                                                                                            | <ul><li>Minimal business impact (Sev C): Within eight business hours</li> <li>Moderate business impact (Sev B): Within four hours</li> <li>Critical business impact (Sev A): Within one hour</li></ul>                                                                                                                                                                   | <ul><li>Minimal business impact (Sev C): within four business hours</li> <li>Moderate business impact (Sev B): Within two hours</li> <li>Critical business impact (Sev A): Within one hour</li> </ul>                                                                                                                                                                    |

Detailed info ca be found [under the link](https://azure.microsoft.com/en-us/support/plans)

### GCP

|              | Standard                                                                                                                                               | Enhanced                                                                                                                                                                                                                                                      | Premium                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Price        | $29/month + 3% of monthly charges                                                                                                                      | $500/month +3% of monthly charges                                                                                                                                                                                                                             | $12.5K/month +4% of monthly charges                                                                                                                                                                                                                                                                                                                                                                                                     |
| Support type | <ul><li>Unlimited individual access to support</li><li>Multi-channel billing and technical support</li><li>Active Assist Recommendations API</li></ul> | <ul><li>Unlimited individual access to support</li><li>Multi-channel billing and technical support</li><li>Active Assist Recommendations API</li><li>Technical Support Escalations</li><li>Cloud Support API</li><li>Third-Party Technology Support</li></ul> | <ul><li>Unlimited individual access to support</li><li>Multi-channel billing and technical support</li><li>Active Assist Recommendations API</li><li>Technical Support Escalations</li><li>Cloud Support API</li><li>Third-Party Technology Support</li><li>Google Cloud Skills Boost</li><li>Event Management Service</li><li>Operational Health Reviews</li><li>Customer Aware Support</li><li>Technical Account Management</li></ul> |
| Resonse time | <ul><li>P2 cases: 4 hours</li> <li>P3 cases: 8 hours</li> <li>P4 cases: 8 hours</li> </ul>                                                             | <ul><li>P1 cases: 1 hour</li><li>P2 cases: 4 hours</li> <li>P3 cases: 8 hours</li> <li>P4 cases: 8 hours</li> </ul>                                                                                                                                           | <ul><li>P1 cases: 15 minutes</li><li>P2 cases: 2 hours</li> <li>P3 cases: 4 hours</li><li>P4 cases: 8 hours</li> </ul>                                                                                                                                                                                                                                                                                                                  |

Detailed info ca be found [under the link](https://cloud.google.com/support)

## Managed services

First of, what are managed services? As per AWS documentation:

`Managed services is an enterprise type of service that provides ongoing management of your cloud infrastructure. It implements best practices and maintains your infrastructure to reduce your operational overhead and risk. It provides full-lifecycle services to provision, run, and support your infrastructure, and automates common activities such as change requests, monitoring, patch management, security, and backup services. It enforces your corporate and security infrastructure policies, and enables you to develop solutions and applications using your preferred development approach.`

Equipped with that knowledge, let's see what Managed Services does each of the vendors offer.

### AWS

- Amazon Elastic Kubernetes Service (EKS)
- Amazon Elastic Compute Cloud (EC2)
- Amazon RDS
- Amazon S3
- AWS Lambda
- Amazon Virtual Private Cloud (VPC)
- Amazon Redshift
- Amazon ElastiCache
- Amazon Athena
- Amazon Simple Notification Service
- Amazon Kinesis
- Amazon Glacier
- AWS App Runner
- Amazon DocumentDB
- Amazon QuickSight
- Amazon Kinesis Data Firehose
- AWS Elemental MediaTailor
- AWS Snowball

### Azure

- Azure Health bot
- Azure AI Document Intelligence
- Azure Spring Apps
- Azure Kubernetes Service (AKS)
- Azure Red hat OpenShift
- Azure Database for MySQL
- Azure Database for PostgreSQL
- Azure Database for MariaDB
- Azure SQL Database
- Azure SQL Managed Instance
- Azure SQL Managed Instance for Apache Cassandra
- Azure Managed Grafana
- Azure Stack Edge
- Azure Managed Applications
- Azure Bastion
- Azure Managed Lustre

### GCP

- Google Kubernetes Service
- Cloud Run
- TensorFlow Enterprise
- API Gateway
- Batch
- Google Kubernetes Engine (GKE)
- Cloud Deploy
- Cloud SQL
- AlloyDB for PostgreSQL
- Cloud Workstations
- Cloud Run for Anthos
- Google Distributed Cloud
- Anthos Service Mesh
- Cloud IDS
- Managed Service for Microsoft Active Directory
- Software Delivery Shield
- Google Cloud Backup and DR
- Parallelstore

## Bibliography

1. https://www.linkedin.com/advice/0/how-do-you-compare-cloud-providers-skills-information-technology
2. https://www.future-processing.com/blog/cloud-services-comparison-market-share-main-differences/
3. https://www.canalys.com/newsroom/global-cloud-services-q1-2023
4. https://www.veritis.com/blog/aws-vs-azure-vs-gcp-cloud-cost-comparison/
5. https://suzukidavid.medium.com/aws-vs-azure-vs-google-cloud-which-free-tier-is-best-73b4889d6dee
6. https://jaychapel.medium.com/aws-vs-azure-vs-google-free-tier-comparison-19b68578e7f
7. https://www.techtarget.com/searchcloudcomputing/feature/A-cloud-services-cheat-sheet-for-AWS-Azure-and-Google-Cloud
8. https://www.techtarget.com/searchcloudcomputing/feature/A-cloud-services-cheat-sheet-for-AWS-Azure-and-Google-Cloud
