Practice Exam Questions and Answers 1 

Domain 4 : Billing and Pricing 90%

Missed Questions
Q : What is the most cost-effective AWS Support Plan if you want the full set of Trusted Advisor checks?
- Business
- Enterprise (my choice)
- Developer
- Basic
A : Business

Explanation
You get 7 core checks for the Developer level and full checks for Business and Enterprise levels.

Domain 3 : Technology 82%

Missed Questions
Q : A Healthcare agency needs to store certain patient information for up to 10 years. To save cost, they want to archive this data to cheaper storage. The data needs to be retrieved within 12 hours. Which is the cheapest option?
- Glacier (my choice)
- Glacier Deep Archive
- S3 Standard IA
- Redshift
A : Glacier Deep Archive

Explanation
This tripped me up because of the time the data needed to be retrieved so let's break down the retrieval times:
Glacier - standard retrieval 3-5 hours, expedited retrieval a few minutes
Glacier Deep Archive - retrieval from 12 - 48 hours 

From the AWS docs "S3 Glacier Deep Archive is up to 75% less expensive than S3 Glacier and provides retrieval within 12 hours using the Standard retrieval speed. You may also reduce retrieval costs by selecting Bulk retrieval, which will return data within 48 hours."

Q : Your design team has recommended the need to distribute incoming traffic across multiple EC2 instances and also across multiple availability zones. Which AWS service can accomplish this?
- CloudFormation
- Auto Scaling Group (my choice)
- CloudFront
- Elastic Load Balancer
A : Elastic Load Balancer

Explanation
The Auto Scaling Group creates and manages scaling out and scaling in the EC2 instances, but it does not handle the distribution of traffic to those instances.
Elastic Load Balancing will distribute the load among the targets.
Can handle single or multi AZs

Q : In order to improve fault tolerance, you would like to begin using services that provide fault tolerance. Which AWS services provide automatic replication across Availability Zones?
- S3
- EC2 (my choice)
- VPC
- DynamoDb
A : S3, DynamoDB

Explanation
I didn't know but guessed EC2. DynamoDB and S3 automaticall replicate to different AZs.

Q : A software company is looking for a tool to automate their deployments from end to end. Which AWS service can provide this continuous delivery functionality?
- CodePipeline
- CodeDeploy (my choice)
- CodeBuild
- CodeCommit
A: CodePipeline

Explanation
I have never heard of most of these. CodeDeploy did deployments when I looked at it earlier so that is why I chose it. According tothe AWS documentation "CodeDeploy is a fully managed deployment service that automates software deployments to a variety of compute services. CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define." So I think the key here is automating all the deployments so yeah CodePipeline is continuous deployments.

CodeCommit - source control system 
CodeBuild - build service that compiles code, runs tests and does builds

Domain 3 : Cloud Concepts 71%

Missed Questions

Q : Your company has decided to use Amazon WorkSpaces. They can use Amazon WorkSpaces to provision either Windows or Linux desktops in just a few minutes. What type of solution is this?
- DaaS
- IaaS
- PaaS (my choice)
- SaaS
A : DaaS

Explanation
Desktop as a service is AWS Workspace where they provision a desktop. What's the difference between IaaS and PaaS?  IaaS is like network, compute, virtualizaiton, storage. And PaaS is primarily for developers creating applications and software. 

Q : You suspect that one of the AWS services your company is using has gone down. How can you check on the status of this service?
- AWS Organizations
- AWS Trusted Advisor (my choice)
- Amazon Inspector
- AWS Personal Health Dashboard
A : AWS Personal Health Dashboard

Explanation
AWS Trusted Advisor gives you guidance but it wouldn't be the place to check out some kind of meltdown. The Personal Health Dashboard is just that.

Q : During Disaster Recovery exercises, you need to re-route traffic from EC2 instances to instances in another region. With which service can you do this?
- Route 53
- VPC Peering
- CloudFront (my choice)
- AWS Auto Scaling
A : Route 53

Explanation
I didn't know but that you might be able to leverage the CloudFront network to move things. CloudFront 

Q : Which AWS service can you use to connect your AWS cloud with an on-premises data center? 
- IAM
- VPC Peering (my choice)
- Internet Gateway
- Virtual Private Gateway
A : Virtual Private Gateway

Explanation
According to AWS docs "VPC peering creates a connection between two VPCs. A virtual private gateway is a logical, fully redundant distributed edge routing function that sits at the edge of your VPC. As it is capable of terminating VPN connections from your on-prem or customer environments".

Q : The CFO of a software company had requested an Executive Summary detailing the advantages of a potential move to the AWS Cloud. What can you say is an advantage of an RDS database over a traditional database?
- AWS maintains the underlying OS and performs software patching on the database.
- It is much easier to convert to a NoSQL database.
- There is much greater access for DBAs.
- It is 5 times faster than traditional databases. (my choice)
A : AWS maintains the underlying OS and performs software patching on the database.

Explanation
The 5x faster piece is not a definitely thing... it COULD BE up to x5 faster. And we already know that patching and OS stuff is managed by AWS for RDS.

Domain 2 : Cloud Concepts 50%

Missed Questions

Q : You need to set up a virtual firewall for your EC2 instance. Which would you use?
- Network ACL (my choice)
- Security Group
- IAM Policy
- Subnet
A : Security Group

Explanation
From the docs "The NACL acts as a firewall, but at the subnet level, not the instance level". Security groups act as a firewall to control inbound and outbound traffic. Security groups act at an instance level not a subnet level.

Q : You are working with IAM and need to attach policies to users, groups, and roles. Which will you be attaching these policies to?
- Entities
- Principals
- Identities
- Resources (my choice)
A : Identities

Explanation
From the docs " Resources are the user, group, role, policy, and identity provider objects that are stored in IAM". It provides access to an account. A resource is just an entity you can work with.

Q : Which policy will provide information on performing penetration testing on your EC2 instances?
- AWS Terms and Conditions Policy
- AWS Acceptable use policy 
- IAM Policy (my choice)
- JSON Policy
A : AWS Acceptable use policy 

Explanation
IAM policies grant permission to AWS resources but they have nothing to do with pentration testing. The accpetable use policy states that penetration testing can be done on your own accounts with AWS approval.

Q : A network security team has noticed some malicious activity on the company AWS account. Which AWS service can be used to detect malicious activity and help protect the account?
- AWS Shield (my choice)
- Amazon GuardDuty
- AWS Inspector
- Amazon Macie
A : Amazon GuardDuty

Explanation
Shield is specifically for DDoS attacks that safe guards applications running on AWS. Amazon GuardDuty is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts and workloads. 

Q : A new application needs temporary access to resources in AWS. How can this best be achieved?
- Store access key in an S3 Bucket and give the application access to the bucket. (my choice)
- Create an IAM Policy and attach it to the application. 
- Create an IAM Role and have the application assume the role.
- Add the application to a group that has the appropriate permissions.
A : Create an IAM Role and have the application assume the role.

Explanation
In order to do my answer, it would need to be a user who can access keys. Access keys are not for temporary access. You want to use an IAM role to manage temporary credentials for applications that run on EC2. The role can specify temporary permissions

Q : In Identity and Access Management, which term refers to the IAM resource objects that AWS uses for authentication?
- Identity
- Principal
- Entity
- Resource (my choice)
A : Entity

Explanation
A resource is a user, policy, role or some kind of identity provider object in IAM. An identity are the resource objects that are used to identify and group. An entity is a resource object that AWS uses for authentication.

Resources
The user, group, role, policy, and identity provider objects that are stored in IAM. As with other AWS services, you can add, edit, and remove resources from IAM. 

Identities
The IAM resource objects that are used to identify and group. You can attach a policy to an IAM identity. These include users, groups, and roles. 

Entities
The IAM resource objects that AWS uses for authentication. These include IAM users, federated users, and assumed IAM roles. 
