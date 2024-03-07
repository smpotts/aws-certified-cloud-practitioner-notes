# Autoscaling & Registering a Domain Name
## Creating a fault-tolerant word press site in the cloud
In EC2
- In Launch Configurations -> Create -> Can add a simple bootstrap in the Launch Configuraitons -> Add web dmz security group
- Create Auto Scaling Group -> start with 2 instances -> Add all the subnets
Add MyWebServer to TargetGroup
- Use scaling policies between 2 and 3 instances based on average cpu untilization
- Grab DNS address of the Load Balancer paste into a tab. Application behind 2 web servers using Load Balancer
- Always delete application Load Balancer after setting it up for testing

## Register a Domain Name
What is DNS?
- DNS : domain name system
- Work like a phone book. Process computers use to resolve domain names to IP addresses

In Route53
Click on Domain registration -> Register Domain
* make sure you have an s3 bucket available with the same name

In S3
Create an S3 bucket with the same name including ".com" part
Properties -> Enable Static website hosting
Enable public access
Permissions -> Add Bucket Policy that allows items in bucket to be public
Add index.html and error.html

In Route53
Fill in registration info
Once it is good click Create Record Set
Click yes to be an alias record
Select s3 bucket we created as the endpoint
*The S3 bucket name MUST be the same as our DNS with the .com at the end
Create

What this does is when you type "acloudguru2019.com" into the browser it will redirect to the s3 bucket and serve the webpages we provided

## Exam Tips
- Route53 is Amazon's DNS service
- DNS service is way for computers to resolve domain names to IP addresses
- Route53 is global similar to IAM
- Can use it to direct traffic all around the world
- Use it to register a domain name
