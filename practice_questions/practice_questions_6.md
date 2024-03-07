Practice Exam Questions and Answers 6

Q: A small software company is starting to work with the AWS Cloud. Which service will allow them to find, test, buy, and deploy software that runs on AWS?
A: AWS Marketplace

Explanation
You can't purchase on the catalog.

Q: You have many database backups that you need to store for an indefinite amount of time. If the backups are ever needed, they just need to be retrieved within 6 hours. What is the lowest cost solution for this scenario?
A: Glacier

Explanation
S3 IA is more expensive than Glacier and also you wouldn't be able to get something out in 6 hours in Deep Archive.

Q: Your company is migrating its services to the AWS cloud. The DevOps team has heard about infrastructure as code, and wants to investigate this concept. Which AWS service would they investigate?
A: AWS CloudFormation

Explanation
Elastic Beanstalk is more for deploying web apps and services that are developed in a language. CloudFormation is an infrastructure tool.

Q: You have joined a small company and inherited an AWS application built within the EC2 Classic network. Which Load Balancer will work with this application?
A: Classic Load Balancer

Explanation
Application load balancers are best for HTTP/S traffic. Classic load balancer is for EC2 isntances and is intended for applications that were built within the EC2 classic network.

Q: A Healthcare agency needs to store certain patient information for up to 10 years. To save cost, they want to archive this data to cheaper storage. The data needs to be retrieved within 12 hours. Which is the cheapest option?
A: Glacier Deep Archive

Explanation
Deep Archive access ranges from 12 - 48 hours

Q: You are trying out AWS on a trial basis and need to deploy an application without having to configure servers. Which AWS service can you use?
A: Elastic Beanstalk

Explanation
FIrst of all I picked ECS - elastic container service. Elastic Beanstalk is for deploying web apps and services

Q: You are working with IAM and need to attach policies to users, groups, and roles. Which will you be attaching these policies to?
A: Identities

Explanation
Principals are a person or application that uses the root account. Think principal of a school. Identities are what you give to a user or group. You give it an identity which is basically defining what it is.

Q: A new application needs temporary access to resources in AWS. How can this best be achieved?
A: Create a role and have the application assume the role.

Explanation
A policy cannot be attached to an application. You need to use roles to attach temporary creds.

Q: Microsoft has announced a new patch for its operating system. For a Platform as a Service solution, who would be responsible for applying the patch?
A: AWS

Explanation
Customer would have to patch the OS for an IaaS solution. PaaS removes the need for customers to manage infrastructure ie you can deploy and manage applications.

