# Security Summary

AWS Artifact 
- is used to retrieve compliance reports

Shared Responsibility model
- AWS responsible for hardware, infrastructure, AZs, compute, storage, networking, edge locations, underlying OSs : security of the cloud
- AWS responsible for patching RDS
- You : matching things on the OS, IAM, encryption
** read the white paper for shared responsibility model

AWS WAF
- web application firewall

AWS Shield
- mitigation service to stop DDOS attacks
- turned on automatically but basic version

AWS Inspector
- installed on EC2 checks vulnerabilities

AWS Trusted Advisor
- inspects whole AWS accounts
- does cost optimization and fault tolerance

AWS CloudTrail
- increases visibility of users resource activity
- based on API calls

Athena
- query data in S3 using SQL
- serverless
- commonly analyzes logs

Macie
- analyzes data in S3 to identify PII
- often used to look at CloudTrail logs 