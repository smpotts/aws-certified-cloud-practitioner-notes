# AWS Inspector vs AWS Trusted Advisor vs CloudTrail

What is Amazon Inspector?
- have to install on EC2 instances
- runs at an operating system level
- automated security assessment service that helps improve security and compliance
- agent that you install on EC2 instance and it will go through and look at common vulnerabilities
- creates a detailed report telling you what you need to fix
- associate this with EC2

What is Trusted Advisor?
- online resource to help you reduce cost, increase performance, improve security
- this is a global service
- a way of having a look at the entire environment and give you a report on it
	1. core checks and recommendations - free and limited
	2. full trusted advisor - business and enterprises only

Cloud Trail vs Cloud Watch
- Cloud Watch monitors performance
- Cloud Trail monitors API calls, everything that is going on in the environment

Exam Tips
- Inspector for EC2
- Trusted Advisor does more than security and looks at the whole env
- CloudTrail records console actions and API calls like a CCTV inside AWS