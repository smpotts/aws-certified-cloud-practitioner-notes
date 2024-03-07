# CloudWatch 101 & AWS System Manager
## CloudWatch 101
**Just need to know what it is

What is CloudWatch?
A monitoring service that watching the performance of your applications
Think personal trainer

What can it monitor?
1. Compute : EC2 instances, autoscaling groups, elastic load balancers, health checks
2. Storage and content delivery : storage gateway, cloud front
3. Monitors underlying physical host : cpu, network, disk

Exam Tips
- remember CloudWatch is used for monitoring performance
- can monitor most of AWS and applications that run on AWS
- can do custom monitoring
- CloudWatch with EC2 monitors every 5 mins by default
- can create CloudWatch alarms
- all about performance
- think personal trainer

## AWS Systems Manager
What is it?
- Allows you to manage EC2 instances at scale
- Can do maintenance windows and patches
- Can use it to manage on prem and in the cloud

How it works
- When you have a fleet (a ton of) EC2 instance you don't want to have to login and manage each and every one individually. You can install something on them and have them mangaed by the AWS Systems Manager
- You can use Systems Manager to do a run command and it will deploy to all instances

Exam Tips
- can be used to manage fleets of EC2 instance or VMs
- a piece of software can be installed on each VM
- can be used inside and outside AWS
- run command is used to install
- integrates with CloudWatch gives you a view of everything