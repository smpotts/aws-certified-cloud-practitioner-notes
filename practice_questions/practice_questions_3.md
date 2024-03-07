Practice Exam Questions and Answers 3 

Domain 1 : Cloud Concepts 88%

Missed Questions
Q : Which of the following is an AWS Global Service?
- CloudFront
- VPC (Selected)
- RDS
- EC2
A : CloudFront

Explanation
VPC is regional. We already know what CloudFront is. Here are the global services that AWS has:
1. IAM
2. Route53
3. CloudFront
4. SNS
5. SES
Also what is SES? That came up on one of the questions... it's simple email service.

Q : An on-premises application requires a consistent, high-speed connection to the AWS Cloud environment that is better than an internet-based connection. Which AWS service can provide this connection?
- Direct Connect
- STS
- AWS VPN (Selected)
- VPC Peering
A : Direct Connect

Explanation
VPN is an internet based connection and the question says it needs to be better than an internet based connection. 

Domain 3 : Technology 82%

Missed Questions
Q : You need to store key-value pairs of users and their high scores for a gaming application. Which is the best option for this type of data?
- RDS MySQL
- Amazon RedShift
- AWS S3 (Selected)
- DynamoDB
A : DynamoDB

Explanation
S3 is better for objects than searching key value pairs. DynamoDB is a key value pair document database.

Q : A developer is trying to programmatically retrieve information from an EC2 instance such as public keys, ip address, and instance id. From where can this information be retrieved?
- CloudWatch Logs
- Instance Snapshot (Selected)
- Instance metadata
- Instance userdata
A : Instance metadata

Explanation
You can create an EC2 snapshot but that is just copying the instance at a point in time, it's not a dashboard or anything like that. The instance metdata has this information.

Q : A gaming company is using the AWS Developer Tool Suite to develop, build, and deploy their applications. Which AWS service can be used to trace user requests from end-to-end through the application?
- AWS X-Ray
- CloudTrail (Selected)
- AWS Inspector
- CloudWatch
A : AWS X-Ray

Explanation
Cloud Trail is more like detailed logs, monitoring and retaining account activity. AWS X-Ray helps developers debug and analyze microservices. You can use it to troubleshoot performance issues and other underlying issues. It provides a view of end to end requests.

Q : You need to launch an EC2 instance in AWS and control access to it. Which AWS service can help with this?
- Amazon Route 53 (Selected)
- Elastic Network Interface
- Amazon RDS
- Amazon Virtual Private Cloud
A : Amazon Virtual Private Cloud

Explanation
Route53 routes end users to applications it does not control access. VPC lets you provision a logically isolated section in the cloud where you can launch a virtual network that you define.

Domain 4 : Billing and Pricing 90%

Missed Questions
Q : A company has signed a 3-year contract with a School District to develop a Teacher Absence Management application. Which type of EC2 instance would be best for application development on this project?
- Scheduled Reserve Instances (Selected)
- Spot Instances
- Standard Reserve Instances
- On-Demand Instances
A : Standard Reserve Instances

Explanation
So dumb!!! Just didn't read the answers all the way through or maybe got confused by the name. Anyway it's Standard Reserved Instance.

Domain 32: Security and Compliance 81%

Missed Questions
Q : Microsoft has announced a new patch for its operating system. For a Platform as a Service solution, who would be responsible for applying the patch?
- The customer for spot instances only.
- Customer (Selected)
- Either can apply this patch.
- AWS
A : AWS

Explanation
The customer would be responsible for patching the OS for an IaaS solution. Platforms as a service removes the need for companies to manage the underlying infrastructure.

Q : After configuring your VPC and all of the resources within it, you want to add an extra layer of security at the subnet level. Which will you use to add this security? 
- Security Group (Selected)
- IAM
- Private IP Address
- Network ACL
A : Network ACL

Explanation
Security Groups act as a virtual firewall but they are at the instance level not the subnet level. A Network ACL is an optional layer of security for the VPC that acts as a firewall for controlling traffic at the subnet level. A subnet is a smaller network inside a larger network.

Q : In Identity and Access Management, which term applies to a person or application that uses the AWS account root user, an IAM user, or an IAM role to sign in and make requests to AWS?
- Resource
- Entity
- Principal
- Identity (Selected)

Explanation
Identities are the resource objects that are used to identify and group. You attach a policy to an identity. A principal is a person or application that uses the root account, IAM user, or a role to sign in and make requests.
