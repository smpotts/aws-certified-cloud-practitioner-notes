# Athena and Macie

What is Athena?
- interactive query services that allows you to query data in S3 using standard SQL
- serverless
- allows you to query logging data, CloudTrail, etc data stored in S3
- no need for ETL
- pay per query or TB scanned
- can use as a dataware house service too

Athena Use Cases
- query log files
- generate business reports on data stored in S3
- analyze cost and usage reports
- run queries on click stream data

What is Macie?
- security service that uses AI to discover, classify and protect sensitive data in S3 
- can see if S3 contains Personally Identifiable Information
- can also analyze CloudTrail logs
- dashboards reporting and alerts
- security service

Exam Tips
- remember what Athena is : queries data in s3, analyzes log data often
- Macie : uses AI to analyze data in S3 and helps identify PII, can analyze CloudTrail logs for suspicious API activity
