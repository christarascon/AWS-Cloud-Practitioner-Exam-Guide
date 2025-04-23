# AWS Cloud Practitioner Exam Guide (CLF-C02)

These study notes are designed to help you with a quick revision before your exam. Whether you are studying for the AWS Cloud Practitioner certification or already hold the certification but wish to keep your study notes handy, this guide will be a valuable resource. Feel free to return as often as you need! These are the same notes I used to prepare for and pass the exam.

![Logo](./images/Cloud-Practitioner.png)

## Table of contents
- [Why AWS CLF-C02 Is Worth Your Investment?](https://www.vmexam.com/blog/why-aws-clf-c02-worth-your-investment)
- [Study Guide](./study-guide.md)
- [Cloud Computing](./sections/cloud_computing.md)
  - What is Cloud Computing?, AWS Global Infrastructure, Shared Responsibility Model
- [IAM: Identity Access & Management](./sections/iam.md)
  - What Is IAM?, Multi-Factor Authentication (MFA), MFA Devices Options in AWS, How Can Users Access AWS?, AWS CLI Overview, AWS SDK Overview
- [EC2: Virtual Machines](./sections/ec2.md)
  - What is Amazon EC2?, Introduction to Security Groups, Classic Ports to Know, EC2 Instance Launch Types, Choosing the Right Purchasing Option, Shared Responsibility Model for EC2
- [EC2 Instance Storage](./sections/ec2_storage.md)
  - EBS Volumes, EFS: Elastic File System, EFS Infrequent Access (EFS-IA), Amazon FSx – Overview, EC2 Instance Store, Shared Responsibility Model for EC2 Storage
- [Elastic Load Balancing & Auto Scaling Groups](./sections/elb_asg.md)
  - Scalability & High Availability, Vertical Scalability, Horizontal Scalability, High Availability for EC2, Scalability vs Elasticity, What is Load Balancing?, Auto Scaling Group Overview
- [Amazon S3](./sections/s3.md)
  - S3 Use Cases, Amazon S3 Overview - Buckets, Objects, S3 Websites, Storage Classes, S3 Object Lock & Glacier Vault Lock, Shared Responsibility Model for S3, AWS Snow Family Overview, Edge Computing, Snow Family in Edge Computing, AWS OpsHub, Hybrid Cloud for Storage, AWS Storage Gateway
- [Databases & Analytics](./sections/databases.md)
  - Overview of Databases, Relational & NoSQL Databases, AWS RDS, Amazon Aurora, Amazon ElastiCache, DynamoDB, Redshift, Amazon EMR, Athena, QuickSight, DocumentDB, Amazon Neptune, Amazon QLDB
- [Other Compute Section](./sections/other_compute.md)
  - Docker, ECS, Fargate, ECR, Serverless Overview, AWS Lambda, API Gateway, AWS Batch, Lightsail Overview
- [Deploying and Managing Infrastructure at Scale](sections/deploying.md)
  - CloudFormation, AWS Cloud Development Kit (CDK), Developer Problems on AWS, Web App 3-Tier Architecture, AWS Elastic Beanstalk, CodeDeploy, CodeCommit, CodeBuild, CodePipeline, CodeArtifact, CodeStar, Cloud9, Systems Manager (SSM), OpsWorks
- [Global Infrastructure](sections/global_infrastructure.md)
  - Why Global Applications Matter, Amazon Route 53, Routing Policies, CloudFront, AWS Global Accelerator, AWS Outposts, Wavelength, Local Zones
- [Cloud Integration](sections/cloud_integration.md)
  - SQS, Kinesis, SNS, MQ Overview
- [Cloud Monitoring](./sections/cloud_monitoring.md)
  - CloudWatch, CloudTrail, X-Ray, CodeGuru, Service Health Dashboard, Personal Health Dashboard
- [VPC](./sections/vpc.md)
  - VPC & Subnet Basics, Internet Gateway, NAT Gateways, Network ACLs & Security Groups, Flow Logs, VPC Peering, VPC Endpoints, VPN & Direct Connect, Transit Gateway Overview
- [Security & Compliance](sections/security_compliance.md)
  - Shared Responsibility Model, DDoS Protection with AWS, AWS Shield, WAF, KMS, CloudHSM, Certificate Manager, Secrets Manager, AWS Artifact, GuardDuty, Inspector, Config, Macie, Security Hub, Detective, Abuse Prevention, Root User Privileges, IAM Access Analyzer
- [Machine Learning](sections/machine_learning.md)
  - Rekognition, Transcribe, Polly, Translate, Lex, Comprehend, SageMaker, Forecast, Kendra, Personalize, Textract
- [Account Management, Billing & Support](sections/account_management_billing_support.md)
  - AWS Organizations, Multi-Account Strategies, Service Control Policies (SCP), Consolidated Billing, Control Tower, Resource Access Manager (AWS RAM), Service Catalog, Pricing Models (Compute, Storage, Databases, CloudFront, Networking)
- [Advanced Identity](sections/advanced_identity.md)
  - STS, Amazon Cognito, Microsoft Active Directory, IAM Identity Center
- [Other AWS Services](sections/other_aws_services.md)
  - WorkSpaces, AppStream 2.0, Sumerian, IoT Core, Elastic Transcoder, AppSync, Amplify, Device Farm, Backup, Elastic Disaster Recovery (DRS), DataSync, Application Discovery Service, Migration Hub, Fault Injection Simulator (FIS), Step Functions, Ground Station, Pinpoint
- [AWS Architecting & Ecosystem](sections/architecting_and_ecosystem.md)
  - Well-Architected Framework Principles, Best Practices for Cloud Design, 6 Pillars of Well-Architected Framework, Right Sizing, AWS Ecosystem, Free Resources, AWS Marketplace

## CLF-C02 Practice Test
Prepare effectively with a set of realistic, exam-style questions tailored to the AWS Certified Cloud Practitioner (CLF-C02) exam. This practice test mirrors the actual exam format and difficulty level—helping you:

- Sharpen your understanding of core AWS services and concepts
- Identify knowledge gaps before the real exam
- Boost your confidence and readiness
- 
- **[👉 Start the Practice Test](https://www.vmexam.com/aws/clf-c02-aws-cloud-practitioner)**

## Other AWS Certification Practice Exams and Blogs

- [AWS Certification Practice Exams](https://www.vmexam.com/aws)
- [How AWS AI Practitioner Certification Opens Doors to High-Paying AI Jobs](https://medium.com/@certifyinsider/how-aws-ai-practitioner-certification-opens-doors-to-high-paying-ai-jobs-62ce8923435c)
- [[9 Steps] Guide to Becoming an AWS Solutions Architect Associate](https://medium.com/@certifyinsider/9-steps-guide-to-becoming-an-aws-solutions-architect-associate-29c3bc5c5762)
- [SCS-C02 Certification FAQs & Study Guide](https://medium.com/@certifyinsider/scs-c02-certification-faqs-study-guide-84261ccdd5de)
- [AWS Certification vs Azure Certification: In-Depth Career Analysis](https://www.linkedin.com/pulse/aws-certification-vs-azure-in-depth-career-analysis-rufina-scott-18c4f/)
