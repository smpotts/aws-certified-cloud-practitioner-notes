# Databases 101
## What is a relational database?
- Think of traditional spreadsheet
- Tables have rows, rows have fields and columns

## Relational Databases on AWS - RDS
- SQL Server
- PostgreSQL
- MySQL
- Oracle
- Aurora
- MariaDB

## RDS has 2 key features
1. Multiple availability zones - for disaster recovery
2. Read replicas - copy of  production database and send EC2 instance to read from those for better performance

Multi-AZ
- Automatically fails over

## Read replicas
- EC2 writes to the primary and writes are replicated to the read replica database
- You can have 5 copies of the primary database
- Can set up the EC2 instances writes to primary and reads from the replica
	- this increases performances because the EC2 instances are reading from 5 different copies of the primary database

## Non Relational Databases
- Collection = table
- Document = row of data
- KV pairs = fields
- Columns in the table can vary and this will not affect the other rows in the database
- Amazon's Non-Relational Database is called DynamoDB
	- used for NoSQL or non relational databases

### OLTP vs OLAP
OLTP: standard queries you run. Pulling a row of transactional data. Taking or inserting a row into a database.
OLAP: net profit for EMEA and Pacific for a product. This pulls a lot of data. Sums things. Adds sales price.

### What is data warehousing?
Used for business intelligence to pull large and complex data sets
Amazon's Data Warehousing tool is called Redshift. Used for analytics

## What is ElastiCache?
- Web service that improves performances of web applications by allowing you to retrieve information from fast managed, in-memory caches instead of relying on disk-based databases
- Supports two open-source in-memory caching engines
- Caches most common queries and returns them a lot faster. Takes a massive load off production database

### Caching Engines
1. Memcached
2. Redis

## Exam Tips
- RDS is for SQL/ OLTP : mysql, postgres, sql server, aurora, mariadb
- DynamoDB : no sql
- Redshift : OLAP analytics, BI
- ElastiCache : in mem caching engine in cloud takes load of prod dbs, redis and memcached. Used for frequent identical queries
