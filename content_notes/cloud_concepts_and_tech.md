# Cloud Concepts and Technology Summary Part 1 & 2
## Part 1

Know the 6 advantages of cloud
1. trade capital for variable expense
2. benefits from economies of scale
3. stop guessing about capacity
4. increased speed and agility
5. stop spending money running and maintaining data centers
6. go global in minutes

Know the 3 Types of Cloud Computing
1. Infrastructure as a service (IAAS) ie EC2
2. Platform as a service (PAAS) ie Elastic Beanstalk
3. Software as a service (SAAS) ie Gmail

Know the 3 types of Cloud computing
1. Public cloud
2. Hybrid
3. Private cloud or on prem cloud

Understand the difference between region and Availability zone
- region is a physical location with two or more AZs
- AZ zone is one or more discrete data centers
- Edge locations are endpoints used for caching

Choosing the right region?
- data sovereignty laws
- latency to end users
- what aws services you need? latest and greatest in N. Virginia

Understand different support packages
- Basic
- Developer $29
- Business $100
- Enterprise $15k you get a TAM

Billing Alerts and alarms will let you know when level of spending has been reached

IAM
- it's global
- root account has admin access
- create a user and use that
- should use mfa
- group is a place to store users ie developers
- to set permissions to a group use a policy

You can access the platform using
1. sdk
2. console
3. command line

S3
- object based, stores files
- o bytes to 5 TB
- unlimited storage
- things stored in buckets
- universal namespace, name must be unique globally
- not suitable for OS install
- upload gives you http 200
- kv pairs
- put is immediate, update or delete takes time eventual consistency
- when you view buckets you view them globally but buckets can have an individual region
- can replicate contents of buckets to another using cross region replication
- transfer acceleration uses edge locations
- bucket policies can make all things in bucket public
- can use s3 to host static website
- scales automatically to meet demand
- objects are stored on multiple servers in multiple facilities

S3 Storage classes
1. s3 standard
2. s3 IA
3. s3 one zone
4. s3 intelligent tiering
5. glacier
6. glacier deep archive

CloudFront
- uses edge locations to cache content for users around the world
- edge locations are where content is cached
- origin is origin of files to distribute
- distribution - name of the CDN
- web distribution used for websites
- rtmp used for media streaming
- can write to edge locations
- objects cached for life of TTL
- can clear cached objects but you will be charged

EC2
- resizable compute capacity
- if spot pricing out of reach you are not charged
- compute based
- need private key to connect
- not serverless, it is a server
- should always have an instance in each AZ

EC2 pricing models
1. on demand
2. reserved
3. spot
4. dedicated hosts - physical instances for regulatory or licenses

Instance Types
F - FPGA
I -  IOPS
G - graphics
H - high disk throughput
T - t2 micro
D - density
R - ram
M - general purpose
C - compute
P - graphics think pics
X - extreme memory
Z - extreme memory and cpu
A - arm based workloads
U - bare metal

EBS
1. SSD : general purpose (GP2) and provisioned iops (IO1)
2. Magnetic : throughput optimized hdd (ST1) and cold hdd (SC1) and magnetic

Common ports
22 - linux
3389 - rdp
80 - http
443 - https

Security groups are virtual firewalls in the cloud
- you need to open ports

## Part 2
Roles
- Roles are more secure than using access key id and secret access keys
- Can apply to EC2 instances
- Global

Load Balancers
1. application
2. network
3. classic - old school
- can make intelligent routing decisions

RDS
- SQL OLTP
- mysql, sql server, maria, postgres, oracle, aurora
- multiple AZs
- read replicas increase performance

DynamoDB
- no sql
 
Redshift
- OLAP
- analytics
- data warehousing
- BI

Elasticache
- caching frequently used database queries
- used on websites

Graph databases
- know that the service is Neptune

Autoscaling
- multiple EC2 instance behind a load balancer

Route53
 - DNS service - resolves domain name to an IP address
- global
- can use it to direct traffic around the world
- can use it to register a domain name

Elastic Beanstalk
- create infrastructure to support code
- upload app and handles the infrastructure
- used if you don't know what to do with AWS

CloudFormation
- used if you do know what to do with AWS
- models and sets up resources
- create a template in json describes resources you want and then takes care of configuring and provisioning

Elastic Beanstalk vs CloudFormation
- both are free but resources they provision are not
- Elastic Beanstalk is limited in what it can provision and is not programmable and CloudFormation can do almost any service and is programmable

Global services
1. IAM
2. Route53
3. CloudFront
4. SNS
5. SES

On prem
1. Snowball
2. Snowball Edge
3. Storage Gateway
4. CodeDeploy (deploy apps)
5. Opsworks (deploy apps)
6. IoT Greengrass

CloudWatch
- monitors performance
- can monitor most of AWS
- with EC2 5 mins by default
- can create alarms
- all about performance

Systems Manager
- manages fleets of EC2 instances and VMs 
- piece of software installed on all machines
- on prem and inside AWS
