## AWS Services Overview

Descriptions of available services.

---
### Brief

#### Compute
- [**EC2**]
  - Elastic Cloud Compute (EC2) provides resizable compute capacity in the cloud. A true virtual computing environment, organizations can launch various compute resources.
- [**Auto Scaling**]
  - Allows scaling EC2 capacity up or down automatically set by defined conditions for workloads.
- [**ELB**]
  - Elastic Load Balancer automatically distributes incoming application traffic across multiple EC2 instances to acheive greater fault tolerance.
- [**Elastic Beanstalk**]
  - Service for deploying and scaling web applications and services
- [Lambda]
  - A zero-administration compute platform that runs backend code on the AWS cloud. Lambda runs on its own AWS EC2 compute fleet across multiple availability zones that provides high availability, security, performance and scalability.
- Server Migration
- EC2 Container Service

#### Storage & Content Delivery
- [S3]
  - Highly scalable object storage
- [Elastic Block Storage]
  - Persistent block level storage volumes for use with EC2 offering consistent and low-latency performance
- [**CloudFront**]
  - Content web delivery service that helps model and setup AWS resources via templates
- [**Glacier**]
  - Storage service optimized for infrequently used data that is rarely retrieved; secure, durable and low-cost for data archiving and long-term backup
- [**Storage Gateway**]
  Connects on-premise software appliances with cloud-based storage providing integration with data security features between on-premise IT environments and AWS storage infrastructure
- Elastic File System
- Snowball

#### Database
- [**RDS**]
  - Service for organizing, maintaining and scaling relational database systems
- [**ElastiCache**]
  - Service for setting up, managing and scaling dristributed in-memory cache environments
- [**DynamoDB**]
  - Fully managed database service that supports both document and key-value data models
- DMS
- Redshift

#### Networking
- [**VPC**]
  - Enables launching AWS resources into a virtual network that is logically isolated and defined by the user/admin
- [**DirectConnect**]
  - Allows establishing a dedicated network connection from external premises to AWS
- [**Route 53**]
  - Highly available and scalable DNS web service that effectively connects user requests to AWS infrastructure

#### Management Tools
- [**CloudWatch**]
  - Monitoring service for AWS cloud resources and applications running on them
- [**CloudFormation**]
  - creation and management of AWS resources, provisioning and updating them orderly and predictably
- [Config]
  - fully managed service providing AWS resource inventory, configuration history, and configuration change notifications enabling security and governance.
- [CloudTrail]
  - web service that records AWS API calls and delivers log files
- Service Catalog
- OpsWorks
- Trusted Advisor

#### Security & Identity
- [**IAM**]
  - Allows secure access control to AWS services and resources for users
- [Certificate Manager]
  - Provision, manage and deploy SSL and TSL certificates for AWS resources
- [Directory Service]
  - Service for connecting AWS resources with existing on-premise Microsoft Active Directory or creating new standalone directory in the cloud
- [WAF]
  - Web Application Firewall for protection from common web exploits
- [KMS]
  - Key Management Service provides creation and control of encryption keys and uses Hardware Security Modules (HSMs) for security of those keys
- Inspector

#### Mobile Services
- [**SNS**]
  - Simple Notification Service is a fully managed pub-sub messaging sercice
- Mobile Hub
- Device Farm
- Cognito
- Mobile Analytics

#### Application Services
- [**API Gateway**]
  - Fully managed service allowing devs to create, publish, maintain, monitor and secure APIs at any scale
- [**Elastic Transcoder**]
  - Highly scalable cloud-based media transcoder
- [**SQS**]
  - Simple Queue Service is a fully managed queueing service allowing transmitting any volume of data at any throughput level
- [**SES**]
  - Simple Email Service is a scalable email service
- [**SWF**]
  - Simple Workflow is a fully managed state tracker and task coordinator
- CloudSearch
- AppStream

#### Enterprise Applications
- WorkSpaces

#### Game Development
- GameLift

#### Developer Tools
- CodeCommit
- [**CodeDeploy**](#CodeDeploy)
  - Service for automating deployments to EC2 instances and instances running on premises.
- CodePipeline

#### Analytics
- EMR
- Elasticsearch Service
- Machine Learning
- Data Pipeline
- Kinesis

### EXPANSIVE
#### Compute
- [**EC2**]
- [**Auto Scaling**]
- [**ELB**]
- [**Elastic Beanstalk**]
- [Lambda]
#### Storage & Content Delivery
- [S3]
- [Elastic Block Storage]
- [**CloudFront**]
- [**Glacier**]
- [**Storage Gateway**]
#### Database
- [**RDS**]
- [**ElastiCache**]
- [**DynamoDB**]
#### Networking
- [**VPC**]
- [**DirectConnect**]
- [**Route 53**]
#### Management Tools
- [**CloudWatch**]
- [**CloudFormation**]
- [Config]
- [CloudTrail]
#### Security & Identity
- [**IAM**]
- [Certificate Manager]
- [Directory Service]
- [WAF]
- [KMS]
#### Mobile Services
- [**SNS**]
#### Application Services
- [**API Gateway**]
- [**Elastic Transcoder**]
- [**SQS**]
- [**SES**]
- [**SWF**]
#### Developer Tools
- CodeCommit
- **CodeDeploy**
- CodePipeline
