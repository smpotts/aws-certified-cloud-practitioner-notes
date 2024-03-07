Practice Exam Questions and Answers 2

1. With S3, standard storage is designed to provide 99.99999999999 precent durability and what percent availability?
99.99

2. Which of the following two services on AWS can you choose to do searches?
AWS CloudSearch and AWS ElasticSearch

3. AWS Glacier is a long-term storage solution that currently starts at what rate per GB per month?
0.004

4. Which Amazon EC2 instance lets you take advantage of unused capacity in the cloud and provides up to a 90% discount compared to on-demand?
Spot instance
Standard reserve only offers up to 75%

5. Which of the following are regarded as regional AWS Services?
EFS
Batch
- EC2 V this is one for sure
- EFS : this is a file system
- Batch : a set of batch management capabilities that enable batch computing jobs. This is used with EC2. This is on the regional services list
- Security Token Service : a web security token service that enables you to request temporary limited credentials for IAM users
- Route53 X know this is not it

How is EFS different from EBS?
EBS is block level storage volumes
The main difference between EFS and EBS is that EBS is only accessible from a single EC2 instance in your particular region while EFS allows you to mount the file system across multiple regions and instances.

Why is EFS a regional service?
By this question they mean the services that are running in different/ multiple regions. Batch can run batch jobs across multiple AZs within a region.
EFS is a regional data storage service that stores data across multiple AZs
EC2 is tied to a particular AZ where it was launched

6. A customer wants to run their app in the cloud via EC2 instances. Their code is stored in Github, what tool can they use to launch their code into EC2 instances?
- AWS CodeCommit : source control service that hosts git repos
- AWS CloudFormation : templates
- AWS CodeDeploy : deployment software that automates deployments to a variety of compute servies like EC2
- AWS Kinesis : collect analyze and process data streams and video in real time
CodeDeploy

7. Company wants a hybrid approach. What can they use to assist them in their estimating costs?
- Total Cost of Ownership Calculator
- Cost Calculator

8. Want to launch a new database where the customer assumes responsibility and management of the guest OS including updates and security patches. Which service should they use?
- Dynamo
- EC2
- Aurora
- DocumentDB

For EC2 you have the control over updates and security patches so you could install any database you want on there.
Aurora us a fully managed service where patching and backups and updates are handled by Amazon. So is DynamoDB and DocumentDB.
EC2

9. Which one is the most suitable to use to store the results of I/O intensive SQL database queries to improve application performance?
- ElastiCache : does the web caching for common queries
- (IoT) Greengrass : compute, messaging, data management and ML to edge devices
- CloudFront : CDN 
- DynamoDB Accelerator : in memory cache for DynamoDB with extreme performance improvements. Only applicable to DynamoDB.

10. Which of the following shares a collection of offerings to help you achieve specific business outcomes related to enterprise cloud adoption through paid engagements in several speciality practice areas?
AWS Professional Services

Storage Gateway
- AWS Storage Gateway connects an on-premises software appliance with cloud-based storage 

4) Which AWS networking service enables a company to create a virtual network within AWS?
A) AWS Config
B )Amazon Route 53
C) AWS Direct Connect
D) Amazon Virtual Private Cloud (Amazon VPC)
