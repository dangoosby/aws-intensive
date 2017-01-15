# AWS Services Overview
Descriptions of available services.

---

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


---

## COMPUTE

### EC2
### Auto Scaling
### EC2 Container Service

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://medium.com/production-ready/a-little-story-about-amazon-ecs-systemd-and-chaos-monkey-8bc7d1b5778?utm_source=clouddevweekly&utm_medium=email
  - https://aws.amazon.com/blogs/compute/introducing-amazon-ecs-task-placement-policies/
  - https://aws.amazon.com/blogs/compute/amazon-ec2-container-service-at-aws-reinvent-2016-wrap-up/
  - https://aws.amazon.com/blogs/compute/introducing-blox-from-amazon-ec2-container-service/
  - 

### ELB

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://www.usenix.org/conference/lisa16/conference-program/presentation/shuff?utm_source=webopsweekly&utm_medium=email

### Elastic Beanstalk
### Lambda

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - http://blog.ryankelly.us/2016/08/07/going-serverless-with-aws-lambda-and-api-gateway.html?utm_source=clouddevweekly&utm_medium=email
  - https://www.dynatrace.com/blog/micro-services-when-micro-becomes-nano/?utm_source=webopsweekly&utm_medium=email
  - https://aws.amazon.com/blogs/compute/managing-your-aws-resources-through-a-serverless-policy-engine/
  - https://aws.amazon.com/blogs/compute/scripting-languages-for-aws-lambda-running-php-ruby-and-go/
  - https://aws.amazon.com/blogs/compute/serverless-at-reinvent-2016-wrap-up/
  -

### Lightsail
### Batch

---

## STORAGE

### S3

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://www.sumologic.com/aws/s3/10-things-might-not-know-using-s3/?utm_source=webopsweekly&utm_medium=email
  -

### Elastic Block Storage
### CloudFront

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://aws.amazon.com/about-aws/whats-new/2016/09/amazon-cloudfront-now-supports-http2/?utm_source=clouddevweekly&utm_medium=email
  -

### Glacier
### Storage Gateway
### Elastic File System

---

## Migration

### DMS
### Server Migration
### Snowball

---

# DATABSE

## RDS

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - http://www.emind.co/blog/aws-aurora-vs-aws-rds-mysql-checklist/?utm_source=clouddevweekly&utm_medium=email
  -

## ElastiCache
## DynamoDB
## Redshift

---

## NETWORKING & CONTENT DELIVERY

### VPC
### DirectConnect
### Route 53

  #### Docs

  ###### *Domain Registration*

  Allows registering new domain names and transferring previously registered domain names.

  ###### *DNS Service*

  Routes internet traffic to applications and other AWS services by translating domain names into IP addresses for newly and previously registered domains.

  ###### *Health Checking*

  Health checks monitor health of resources

  ###### *Hosted Zones*

  A collection of resource record sets hosted by R53 that are managed under a single domain name with the same suffix

  ###### *Supported DNS Resource Record Types*
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

  ###### *DNS Constraints and Behaviors*

    - Max Response Size : Responses sent over UDP are limited to 512 bytes. If resolver supports EDNS0, R53 permits responses up to 4096 bytes over UDP without truncation.
    - Authoritative Section Processing : R53 appends NS resource record set for the relevant hosted zone to authority section of DNS response for successful queries, whereas R53 appends start of SOA record on failed queries.
    - Additional Section Processing : R53 appends resource records to the Additional section

  ###### *R53 Pricing*

    Pay only for hosted zones configured and number of queries R53 answers.

  #### Practical

  ###### *Subheading*
  - https://aws.amazon.com/about-aws/whats-new/2016/08/amazon-route-53-announces-naptr-record-support-and-dns-query-test-tool/?utm_source=clouddevweekly&utm_medium=email
  - https://www.awsarchitectureblog.com/2014/12/internet-routing.html
  - https://www.awsarchitectureblog.com/2014/03/aws-and-compartmentalization.html
  -

---

## MANAGEMENT TOOLS

### CloudWatch
### CloudFormation
### Config
### CloudTrail
### Service Catalog
### OpsWorks
### Trusted Advisor
### Managed Services
### Application Discovery Service

---

## SSECURITY, IDENTITY & COMPLIANCE

### IAM

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://medium.com/@kavehmz/use-aws-roles-and-secure-your-access-with-mfa-7a7babfd123a#.u1dor0764
  - https://aws.amazon.com/blogs/security/the-top-20-most-viewed-aws-iam-documentation-pages-in-2016/
  -

### Certificate Manager
### Directory Service
### WAF and Shield
### KMS
### Inspector
### Compliance Reports
### General

  #### Practical

  ###### *Subheading*
  - https://aws.amazon.com/blogs/security/the-top-10-most-downloaded-aws-security-and-compliance-documents-in-2016/
  - https://aws.amazon.com/blogs/security/the-most-viewed-aws-security-blog-posts-in-2016/

---

## MOBILE SERVICES

### Mobile Hub
### Device Farm
### Cognito
### Mobile Analytics
### Pinpoint

---

## MESSAGING

### SNS
### SQS
### SES

---

## APPLICATION SERVICES

### API Gateway

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - http://blog.ryankelly.us/2016/08/07/going-serverless-with-aws-lambda-and-api-gateway.html?utm_source=clouddevweekly&utm_medium=email
  -

### Elastic Transcoder
### SWF
### Step Functions

---

## DESKTOP & APP STREAMING

### WorkSpaces
### AppStream 2.0

---

## GAME DEVELOPMENT

### GameLift

---

## BUSINESS PRODUCTIVITY

### WorkDocs
### WorkMail

---

## DEVELOPER TOOLS

### CodeCommit

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://aws.amazon.com/blogs/devops/introducing-git-credentials-a-simple-way-to-connect-to-aws-codecommit-repositories-using-a-static-user-name-and-password/
  -

### CodeBuild
### CodeDeploy
### CodePipeline

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://aws.amazon.com/blogs/devops/integrating-git-with-aws-codepipeline/
  -

---

## ANALYTICS

### EMR
### Elasticsearch Service

  #### Docs

  ###### *Subheading*

  Lorem Ipsum Bla Bla

  #### Practical

  ###### *Subheading*
  - https://grey-boundary.io/field-notes-elasticsearch-at-petabyte-scale-on-aws/?utm_source=clouddevweekly&utm_medium=email
  - https://aws.amazon.com/about-aws/whats-new/2016/07/amazon-elasticsearch-service-now-supports-elasticsearch-2-3/?utm_source=clouddevweekly&utm_medium=email
  -

### Data Pipeline
### Kinesis
### Athena
### CloudSearch
### QuickSight

---

## ARTIFICIAL INTELLIGENCE

### EMR
### Data Pipeline
### Kinesis
### Athena
### CloudSearch
### QuickSight
### Lex
### Polly
### Rekognition
### Machine Learning

---

## INTERNET OF THINGS

### AWS IoT

---
