# Billing and Pricing Summary

Pay for what you use
Pay less when you reserve more
Even less when you reserve capacity

Capex vs Opex
- capex is capital expenditure you pay up front. Sunk cost, fixed
- opex is operational expenditure pay for what you use like utility billing

EC2 Pricing Models
1. on demand
2. reserved
3. spot
4. dedicated hosts

Free services
- VPC
- Elastic beanstalk
- CloudFormation
- IAM
- Auto scaling
- Opsworks
- Consolidated Billing

** need to read the white paper

Budgets vs Cost Explorer
- budget predicts costs before and cost explorer looks at costs after

Support Plans
1. basic - free
2. developer - business hour email support
3. business - 24/7 email call chat
4. enterprise - you get a TAM and 24/7 support

Tags
- kv pairs attached to resources
- metadata
- can be inherited

Resource groups 
- group resources based on tags they have
- can control and execute automation of EC2 fleets using Systems Manager

Tag Editor
- discover resources and add them

Organizations 
1. full access - root acct with different org units, and they have access to accounts. Can apply. policies to them
2. just with consolidated billing

Best Practices
- use mfa and strong pw

Linked Account
- can have 20 but can request more

Billing Alerts
- when monitoring paying accounts, billing data for them all is included
- can set up individual ones too

CloudTrail
- per account and is enabled per region
- use it to consolidate logs across all the accounts

Consolidated billing 
- allows volume discounts across all accounts
- unused reserved instances are applied across the group

Quick Start
- deploy quickly with CloudFormation templates

Landing Zone
- set up multi aws account 
- sets up 4 accounts

Simply Monthly Calculator
- calculate running costs on monthly basis

Total cost of ownership
- compare on prem vs in cloud
- generates reports

** need to play with the calculators
