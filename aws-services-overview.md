# AWS Services Overview
Descriptions of available services.

---
## BRIEF

| Compute | Summary |
| :--: | :-- |
| EC2 | Elastic Cloud Compute (EC2) provides resizable compute capacity in the cloud. A true virtual computing environment, organizations can launch various compute resources.  |
| Auto Scaling | Allows scaling EC2 capacity up or down automatically set by defined conditions for workloads. |
| ELB | Elastic Load Balancer automatically distributes incoming application traffic across multiple EC2 instances to acheive greater fault tolerance. |
| Elastic Beanstalk | Service for deploying and scaling web applications and services |
| Lambda | A zero-administration compute platform that runs backend code on the AWS cloud. Lambda runs on its own AWS EC2 compute fleet across multiple availability zones that provides high availability, security, performance and scalability. |
| EC2 Container Service | Container management service that supports Docker containers allowing easily run applications on a managed cluster of EC2 instances. |
| Lightsail | -- |
| Batch | -- |
<br>

| Storage | Summary |
| :--: | :-- |
| S3 | Highly scalable object storage |
| Elastic Block Storage | Persistent block level storage volumes for use with EC2 offering consistent and low-latency performance |
| Glacier | Storage service optimized for infrequently used data that is rarely retrieved; secure, durable and low-cost for data archiving and long-term backup |
| Storage Gateway | Connects on-premise software appliances with cloud-based storage providing integration with data security features between on-premise IT environments and AWS storage infrastructure |
| Elastic File System | -- |
<br>

| Migration | Summary |
| :--: | :-- |
| DMS | -- |
| Server Migration | -- |
| Snowball | -- |
<br>

| Database | Summary |
| :--: | :-- |
| RDS | Service for organizing, maintaining and scaling relational database systems |
| ElastiCache | Service for setting up, managing and scaling dristributed in-memory cache environments |
| DynamoDB | Fully managed database service that supports both document and key-value data models |
| Redshift | -- |
<br>

| Networking & Content Delivery | Summary |
| :--: | :-- |
| VPC | Enables launching AWS resources into a virtual network that is logically isolated and defined by the user/admin |
| DirectConnect | Allows establishing a dedicated network connection from external premises to AWS |
| Route 53 | Highly available and scalable DNS web service that effectively connects user requests to AWS infrastructure |
| CloudFront | Content web delivery service that helps model and setup AWS resources via templates |
<br>

| Management Tools | Summary |
| :--: | :-- |
| CloudWatch | Monitoring service for AWS cloud resources and applications running on them |
| CloudFormation | Creation and management of AWS resources, provisioning and updating them orderly and predictably |
| Config | Fully managed service providing AWS resource inventory, configuration history, and configuration change notifications enabling security and governance. |
| CloudTrail | Web service that records AWS API calls and delivers log files |
| Service Catalog | -- |
| OpsWorks | -- |
| Trusted Advisor | -- |
| Managed Services | -- |
| Application Discovery Service | -- |
<br>

| Security, Identity & Compliance | Summary |
| :--: | :-- |
| IAM | Allows secure access control to AWS services and resources for users |
| Certificate Manager | Provision, manage and deploy SSL and TSL certificates for AWS resources |
| Directory Service | Service for connecting AWS resources with existing on-premise Microsoft Active Directory or creating new standalone directory in the cloud |
| WAF and Shield | -- |
| KMS | Key Management Service provides creation and control of encryption keys and uses Hardware Security Modules (HSMs) for security of those keys |
| Inspector | -- |
| Compliance Reports | -- |
<br>

| Mobile Services | Summary |
| :--: | :-- |
| Mobile Hub | -- |
| Device Farm | -- |
| Cognito | -- |
| Mobile Analytics | -- |
| Pinpoint | -- |
<br>

| Messaging | Summary |
| :--: | :-- |
| SNS | Simple Notification Service is a fully managed pub-sub messaging sercice |
| SQS | Simple Queue Service is a fully managed queueing service allowing transmitting any volume of data at any throughput level |
| SES | Simple Email Service is a scalable email service |
<br>

| Application Services | Summary |
| :--: | :-- |
| API Gateway | Fully managed service allowing devs to create, publish, maintain, monitor and secure APIs at any scale |
| Elastic Transcoder | Highly scalable cloud-based media transcoder |
| SWF | Simple Workflow is a fully managed state tracker and task coordinator |
| Step Functions | -- |
<br>

| Desktop & App Streaming | Summary |
| :--: | :-- |
| WorkSpaces | -- |
| AppStream 2.0 | -- |
<br>

| Game Development | Summary |
| :--: | :-- |
| GameLift | -- |
<br>

| Business Productivity | Summary |
| :--: | :-- |
| WorkDocs | -- |
| WorkMail | -- |
<br>

| Developer Tools | Summary |
| :--: | :-- |
| CodeCommit | -- |
| CodeBuild | -- |
| CodeDeploy | Service for automating deployments to EC2 instances and instances running on premises. |
| CodePipeline | -- |
<br>

| Analytics | Summary |
| :--: | :-- |
| EMR | -- |
| Elasticsearch Service | -- |
| Data Pipeline | -- |
| Kinesis | -- |
| Athena | -- |
| CloudSearch | -- |
| QuickSight | -- |
<br>

| Artificial Intelligence | Summary |
| :--: | :-- |
| Lex | -- |
| Polly | -- |
| Rekognition | -- |
| Machine Learning | -- |
<br>

| Internet of Things | Summary |
| :--: | :-- |
| AWS IoT | -- |
<br>



## EXPANSIVE

### Compute

#### EC2
#### Auto Scaling
#### EC2 Container Service

*Subheading*

Lorem Ipsum Bla Bla

*Subheading*

Lorem Ipsum Bla Bla

#### ELB
#### Elastic Beanstalk
#### Lambda
#### Lightsail
#### Batch

---

### Storage

#### S3
#### Elastic Block Storage
#### CloudFront
#### Glacier
#### Storage Gateway
#### Elastic File System

---

### Migration

#### DMS
#### Server Migration
#### Snowball

---

### Database

#### RDS
#### ElastiCache
#### DynamoDB
#### Redshift

---

### Networking & Content Delivery

#### VPC
#### DirectConnect
#### Route 53

*Domain Registration*

Allows registering new domain names and transferring previously registered domain names.

*DNS Service*

Routes internet traffic to applications and other AWS services by translating domain names into IP addresses for newly and previously registered domains.

*Health Checking*

Health checks monitor health of resources

*Hosted Zones*

A collection of resource record sets hosted by R53 that are managed under a single domain name with the same suffix

*Supported DNS Resource Record Types*
  - A : Value is an IPv4 address in dotted decimal notation
  - AAAA : Value is an IPv6 address in colon-separated hexidecimal format
  - CNAME : Value is a domain name
  - MX : An MX record contains decimal number (priority) and domain name
  - NS : Identifies the name servers for the hosted zone; a domain name
  - PTR : Same as domain name
  - SOA : Provides info about a dpomain and corresponding hosted zone
  - SPF : Formerly used to verify email sender identity
  - SRV : Value consists of 4 space-separated values
  - TXT : Record contains a space-separated list of double-quoted strings

*DNS Constraints and Behaviors*

  - Max Response Size : Responses sent over UDP are limited to 512 bytes. If resolver supports EDNS0, R53 permits responses up to 4096 bytes over UDP without truncation.
  - Authoritative Section Processing : R53 appends NS resource record set for the relevant hosted zone to authority section of DNS response for successful queries, whereas R53 appends start of SOA record on failed queries.
  - Additional Section Processing : R53 appends resource records to the Additional section

*R53 Pricing*

  Pay only for hosted zones configured and number of queries R53 answers.

---

### Management Tools

#### CloudWatch
#### CloudFormation
#### Config
#### CloudTrail
#### Service Catalog
#### OpsWorks
#### Trusted Advisor
#### Managed Services
#### Application Discovery Service

---

### Security, Identity & Compliance

#### IAM
#### Certificate Manager
#### Directory Service
#### WAF and Shield
#### KMS
#### Inspector
#### Compliance Reports

---

### Mobile Services

#### Mobile Hub
#### Device Farm
#### Cognito
#### Mobile Analytics
#### Pinpoint

---

### Messaging

#### SNS
#### SQS
#### SES

---

### Application Services

#### API Gateway
#### Elastic Transcoder
#### SWF
#### Step Functions

---

### Desktop & App Streaming

#### WorkSpaces
#### AppStream 2.0

---

### Game Development

#### GameLift

---

### Business Productivity

#### WorkDocs
#### WorkMail

---

### Developer Tools

#### CodeCommit
#### CodeBuild
#### CodeDeploy
#### CodePipeline

---

### Analytics

#### EMR
#### Elasticsearch Service
#### Data Pipeline
#### Kinesis
#### Athena
#### CloudSearch
#### QuickSight

---

### Artificial Intelligence

#### EMR
#### Elasticsearch Service
#### Data Pipeline
#### Kinesis
#### Athena
#### CloudSearch
#### QuickSight
#### Lex
#### Polly
#### Rekognition
#### Machine Learning

---

### Internet of Things

#### AWS IoT

---
