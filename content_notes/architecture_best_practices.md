# Architecting For The Cloud Best Practices 1 & 2

## Part 1
Based off the white paper

Traditional vs Cloud Computing
- IT assets as provisioned resources
- Cloud computing is global, available and scalable
- Higher level managed services - ie machine learning 
- Built-in security
- Architecting for cost - design env in the cloud to be cost efficient
- Operations on AWS

Scalability
1. Scale up - increasing the amount of RAM or CPU
2. Scale out - add more virtual machines behind load balancer
	a. Stateless Applications
	b. Distribute load to multiple nodes
	c. Stateless components
	d. Stateful components
	e. Implement Session affinity
	f. Distributed processing and implement distributed processing

Disposable Resources Instead of Fixed Servers
- Instantaneous Compute Resources
	- Bootstrapping
	- Golden Images : took image of EC2 instance  after configured so when deploying a new one with that image, things are already installed on it
	- Containers
	- Hybrid
- Infrastructure as Code
	- CloudFormation

Automation
- Serverless management and deployment
- Infrastructure management and deployment
	- Elastic Beanstore
	- AWS EC2 Auto recovery
	- Auto scaling
- Alarms and Events
	- CloudWatch alarms
	- CloudWatch events - configure events to detect ex that someone has uploaded a file. Env proactively responding to change in env
	- AWS Lambda schedule events
	- AWS WAF security automations

Loose Coupling
- Distributed systems best practives
	- Graceful failure in practice

Services Not Servers
- Managed servers
- Serverless Architectures

## Part 2

Databases
Relational Databases (Aurora)
Scalability
High Availability Multi AZ
Used when you have complex transactions and joins

Non-relational Database (DynamoDB)
Scalability
High Availability
No join or complex transactions
Don't use for binary files

Data Warehouse (Redshift)
Scalability
High Availability
Not meant for OLTP

Search
CloudSearch and ElasticSearch

Graph databases
Amazon Neptune

Managing increasing volumes of data
An approach to storing large volumes of data. S3 is a great place to create a data lake

Removing single points of fialure
- Introduce redundancy
- Detect failure
- Durable storage
- Automated multi data center resiliance
- Fault isolation and horizontal scaling
- Sharding : split it across multiple shards

Optimize for cost
- Choosing the right size
- Elasticity
- Take advantage of the variety of purchasing options

Caching
1. Application caching
2. Edge caching

Security
- Share security responsibility with AWS
- Use the features for defense
- Reduce privileged access
- Security as code
- Real time auditing

Read this https://d1.awsstatic.com/whitepapers/aws-overview.pdf

Exam Tips
- Read the white paper the day before the exam
