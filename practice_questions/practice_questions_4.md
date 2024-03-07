Practice Exam Questions and Answers 4

Question 4:
Which of the following are examples of AWS-Managed Services, where AWS is responsible for the operational and maintenance burdens of running the service? (Choose TWO)
- VPC (Selected)
- EC2
- EMR
-DynamoDB
- IAM (Selected)
Answer: EMR, DynamoDB

Explanation
EMR and DynamoDB are managed services. Amazon handles all the provisioning of the EMR cluster. Amazon is responsible for performaning all operations tasks to keep the service running. Other Managed services include Redshift, Lambda, RDS, CloudFront. You are responsible for provisioning everything inside the VPC and IAM basically enables you to manage these things by yourself.

Question 5:
What does AWS Snowball provide?
Answer: Secure transfer of data in and out of AWS

Explanation
I didn't think you could move it out of AWS with snowball. Remember it is petabyte scale. Can be done in and out of the cloud at 1/5 the cost of doing it via high speed internet.

NOTES:
- AWS Support Concierge is the billing support team
- As part of the Enterprise support plan the Infrastructure Eveent Management team provides guidance on architecture and scaling
- Responsibilities vary depending on services used for the shared responsibility model

Question 14:
Which of the following services allows customers to manage their agreements with AWS?
Answer: AWS Artifact

Explanation
Artifact is a portal that contains AWS' compliance documentation and agreements. Certificate Manager lets you provision and deploy SSL certificates.

Question 15:
Which service is used to ensure that messages between software components are not lost if one or more components fail?
Answer: SQS 

Explanation
SQS sends and received messages between components. Direct Connect establishes a dedicated network connection between on prem and the cloud.

Question 17:
Select TWO examples of the AWS shared controls.
Answer: Patch and configuration management

Explanation
Configuration management is AWS maintaining the configurations for its infrastructure. VPC is the customers responsibility.

Question 21: 
Hundreds of thousands of DDoS attacks are recorded every month worldwide. What service does AWS provide to help protect AWS Customers from these attacks? (Choose TWO)
Answer: WAF, Shield

Explanation
Cognito allows you to add user signups to mobile apps.

Question 23:
What does AWS provide to deploy popular technologies - such as IBM MQ - on AWS with the least amount of effort and time?
Answer: AWS Quick Start reference documents

Explanation
The Quick Start reference docs provide architecture outlines for popular solutions on AWS. Opworks is a configuration management service that does thinks like Chef and Puppet.

Question 30:
A company is concerned that they are spending money on underutilized compute resources in AWS. Which AWS feature will help ensure that their applications are automatically adding/removing EC2 compute capacity to closely match the required demand?
Answer: Auto Scaling

Explanation
I didn't really read the question... automatically adding or removing capacity. I thought it had to do with looking at previous usage.

Question 39:
What does the AWS Personal Health Dashboard provide? (Choose TWO)
Answer: Personalized view of health services, detailed troubleshooting guidance to address events impacting your systems

Explanation
This was kind of a guess. I didn't think it could do any troubleshooting. Basically it provides alerts and remediation guidance.

Question 40:
According to the AWS Acceptable Use Policy, which of the following statements is true regarding penetration testing of EC2 instances?
Answer: Penetration testing can be performed by the customer on their own stuff without permission

Explanation
Ok so customers can perform penetration testing on their own stuff but it has to be in alignment with AWS' policies.

Question 52:
You have AWS Basic support, and you have discovered that some AWS resources are being used maliciously, and those resources could potentially compromise your data. What should you do?
Answer: AWS Abuse Team

Explanation
Anyone can report abuse of AWS resources. The security team is responsible for security of the AWS services.

Question 58:
Which of the following is not a benefit of Amazon S3? (Choose TWO)
Answer: S3 can be scaled manually and store and retrieve any amount of data from anywhere, S3 can run any type of application or backend system

Question 65: Incorrect
What is the AWS service that provides a virtual network dedicated to your AWS account?
Answer: VPC

Explanation
VPC carves out part of the cloud that is dedicated to your account. VPN is just establishing a secure and private tunnel from your network or device to the internet.
