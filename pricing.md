# Pricing 101

How Pricing Works Whitepaper (20-30% of the exam)

White Paper
Pay as you go for what you use
Pay less the more you use
Pay even less when you reserve capacity

Different Pricing Models

Capex vs opex
- Capex : capital expenditure where you pay up front and it's a fixed sunk cost
- Opex : operational expenditure. Like utility billing. Paying for what you're using

Pricing Policies
1. Pay as you go
2. Pay less when you reserve
3. Pay even less per unit when using more
4. Pay less as AWS grows
5. Custom pricing

Understand the fundamentals (drivers of cost)
1. Compute
2. Storage
3. Data outbound

Start early with cost optimization
- Start early and put cost controls in place before you create these massive environments

Maximizing the power of flexibility
- AWS services are priced independently and transparently
- You can choose and pay for exactly what you need
- You dont pay for them when they are not running. You can turn things off you don't need to use

Using the right pricing model for the job
- the 4 pricing models
- free usage tier

What services are free?
- Amazon VPC - virtual data center in the cloud
- Elastic Beanstalk
- CloudFormation
- IAM
- Auto Scaling
- Opsworks
- Consolidated Billing

EC2 Pricing - What Determines Price?
- clock hours of server time
- instance type
- pricing model
- number of instances
- type of load balancing
- detailed monitoring (monitoring every 1 minute instead of 5)
- auto scaling
- elastic ip addresses
- OSs and software packages

Reserved Instances
- reserve capacity and receive discounts
- more paid up front the more you will save
- longer the contract the more you save

What is Lambda?
- Lambda is a serverless way of doing compute
- Functions only last for a second and return a result

What Determines Price for Lambda?
1. Request Pricing
	a. Number of requests : 1 million requests per month for free tier
	b. $0.20 per million requests after that
2. Duration Pricing
	a. How long the functions are executing for
3. Additional charges
	a. If function transfers data
	b. If the function uses other services

What Determines the Price for EBS?
1. Volumes
2. Snapshots
3. Data transfers

What Determines the Price for S3?
1. Storage class
2. How much you're storing
3. Number of requests
4. Data transfer

What Determines the Price for Glacier?
1. Storage
2. Data Retrieval Times : faster retrieval the more expensive

What is Snowball?
- Petabyte scale data transfer solution that transfers data in and out of the cloud.
- Gigantic disk to move data in to AWS

What Determines Price for Snowball?
- Service fee per job : the bigger the snowball the more expensive
- Daily charge
- Data transfer into S3 is free, transfer out of S3 is not

What Determines Price for RDS?
- clock hours of server time
- type of database
- database instance types ie size
- provisioned storage
- requests
- deployment types
- data transfer

What Determines Price for DynamoDB?
- read
- write
- amount of data you're storing

What Determines Price for CloudFront?
- traffic distribution
- requests
- data transfer out

Read the white papers:
https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf

Exam Tips
- capex (upfront)  vs opex (what you use)
- EC2 pricing models
- remember the free services
- remember provisioning services are free but resources are not
- read the "how aws pricing works" whitepaper
