Practice Exam Questions and Answers 7

Q: A company has developed a media transcoding application in AWS. The application is designed to recover quickly from hardware failures. Which one of the following types of instance would be the most cost-effective choice to use?
A: Spot Instances

Explanation
The whole piece about it having to recover quickly made me think it needed to be up all the time. According to Udemy recover quickly from failures means it can handle interruptions.

Migration Acceleration Program - helps enterprises migrate to the cloud with consulting and training.

PinPoint - service that is used to send customers targeted emails, mesages etc.

Q: Which of the following AWS Services helps with planning application migration to the AWS Cloud?
A: Application Discovery Service

Explanation
Helps identify applications running on prem, their dependencies and performance profiles to help plan cloud migration.

Migration Hub - single location to track progress of application migrations across multiple AWS solutions.

Q: Which of the following are factors in determining the appropriate database technology to use for a specific workload? (Choose TWO)
A: The number of reads and writes per second, the nature of the queries

Explanation
The nature of the read writes is a major consideration when choosing which type of database technology to use. Nature of the queries obviously because thinking about if they are analytical/ if they might be KV pairish. Why not data sov? Ah, this is a consideration when deciding which region to choose. That's what I was thinking of.

Remeber Lambda executes code only when triggered by events.

Amazon Aurora is the only database that scales automatically.

Q: Which support plan includes AWS Support Concierge Service?
A: Enterprise Support

Explanation
It's only available for Enterprise.

QuickSight is a business analytics service.

Q: A company has hundreds of VPCs in multiple AWS Regions worldwide. What service does AWS offer to simplify the connection management among the VPCs?
A: Transit Gateway

Explanation
Transit Gateway is a network transit hub that interconnects all the customer's VPCs. Security Groups can control instance traffic but cannot connect to VPCs.

Q: What is the framework created by AWS Professional Services that helps organizations design a road map to successful cloud adoption?
A: CAF

Explanation
Cloud adoption framework. Used to help companies create a roadmap to get to the cloud.

Batch - computing service that helps you run batch jobs.

Q: Which of the following are use cases for Amazon S3? (Choose TWO)
A: Media store for CloudFront services, hosting static websites

Explanation
Oh this answer literally meant storing databases which should be stored in EBS.

Q: What is the main purpose of using Amazon SWF?
A: Coordinated tasks across distributed application components

Explanation
SFS is simple workflow service that coordinates work across distributed application componets.

Q: What are AWS shared controls?
A: Controls that apply to the infrastructure and the customer layers

Explanation
Customers do not secure the infrastructure.

Q: Which of the following AWS services scale automatically without your intervention? (Choose TWO)
A: Lambda, S3

Explanation
EFS scales automatically not EBS. Lambda dynamically scales function execution.

Q: Which of the following allows you to create new RDS instances? (Choose TWO)
A: CloudFormation, Management Console

Q: What are the benefits of using DynamoDB? (Choose TWO)
A: low lantency, scales to meet required throughput

Explanation
Serverless, highly available, performance at scale

Q: What does AWS Service Catalog provide?
A: simplifies organizing and governing commonly deployed IT services

Explanation
Allows for creating and managing catalogs of IT services that are approved by AWS. Helps meet governance and compliance requirements. Each customer creates their own service catalogs.

Q: What are the benefits of implementing a tagging strategy for AWS resources? (Choose TWO)
A: Quickly identify resources for a project, tracking AWS spending across multiple resources

Explanation
You can't use tags to find deleted resources, the metadata will be gone with it.

AMI - Amazon Machine Images helps you launch an instance from another instance

Q: A developer needs to set up an SSL security certificate for a client's eCommerce website in order to use the HTTPS protocol. Which of the following AWS services can be used to deploy the required SSL server certificates? (Choose TWO)
A: IAM, ACM

Explanation
ACM - Amazon Certificate Manager
Directory service - is an active directory in the cloud. It can be used to manage SSO to apps and services and users as well as create group policies.

Q: Which AWS Service provides the current status of all AWS Services in all AWS Regions?
A: AWS Service Health Dashboard

Explanation
Service health dashboard publishes up to date information about the service availability. Personal health dashboard gives you a general status of the services
