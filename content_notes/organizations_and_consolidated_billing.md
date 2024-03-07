# AWS Organizations and Consolidated Billing

What is AWS Organizations?
- Account management service that enables you to consolidate multiple accounts into an organization that you centrally manage
- Available in two feature sets: consolidated billing and all features
- You get consolidated billing as part of this
- it's a global service
- invite or create an account using the account id if you are inviting

How Consolidated Billing Works
You have a paying account and linked accounts like dev, prod, back office and the linked accounts are independent. Paying account is independent and cannot access the resources of the other accounts.

Advantages of Consolidated Billing
- One bill per account
- Volume pricing discount

Best Practices with AWS Organizations
- use strong pw
- use MFA
- paying account for billing purposes only

What is CloudTrail?
Auditing tool monitors API calls

CloudTrail vs CloudWatch
- CloudWatch monitors performance (used in EC2 a lot) and does auto scailing
- CloudTrail monitors API calls within the AWS platform. It keeps track of everything you create and provision within the AWS environment

How to use CloudTrail with AWS Organizations
- consolidate logs into S3 bucket
- per AWS account and is enabled per region

Exam Tips
- organizations comes in 2 flavors: 1 full access and 2 with just consolidated billing
- enable MFA w/ strong pw
- paying account for billing only
- linked accounts you can only have 20 but they can increase it
- billing alerts: for paying account includes linked accounts, and you can do individual ones too
- CloudTrail : auditing what people are doing in the platform. On a per-account basis. Can be used to consolidate logs
- Consolidated billing gets you volume discount across all accounts
- organization allows you to create organizational units and attach accounts to them
- root account cannot invite a root account

