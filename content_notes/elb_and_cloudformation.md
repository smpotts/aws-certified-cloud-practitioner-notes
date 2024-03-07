# Elastic Beanstalk & CloudFormation
## Elastic Beanstalk
What is it?
- Allows us to provision EC2 instances, load balancers, bootstraps etc.
- Way of deploying resources
- Deploying applications to the cloud

*Exam question : Name all the compute services

## Exam Tips
- remember allows you to deploy and manage applications in AWS without worrying about the infratructure that runs the applications
- handles capacity provisioning, load balancing, scaling and health monitoring

## Cloud Formation
Consists of stacks

Create stack
- choose WordPress blog template
- creates different things based on the template
- can install software, create EC2 and RDS instances
- You can design your own templates

Output - a url that we can use to connect to our environment

## Exam Tips
- CloudFormation helps you model and setup AWS resources
- create a template that describes all the resources you want
- takes care of configuring and provisioning
- Elastic Beanstalk and CloudFormation are free but not the resources they create
- CloudFormation is completely programmable and Elastic BeanStalk is not`