# Using the Command Line & Using Roles

## Getting on ec2 instance
- In IAM check out users
- Re-download access key if you don't have it saved
- ssh ec2-user@public+ip -i MyPrivateKey.pem
- sudo su

## Using S3
- aws s3 mb s3://acloudguru2019-ccp >> unable to locate credentials
*need to enable ec2 to talk to s3
- configure credentials by >> aws configure
- paste access key id and secret access key
- try again >> aws s3 mb s3://acloudguru2019-ccp
- list buckets >> aws s3 ls
- create file echo "hello" > hello.txt
- copy the file to s3 >> aws s3 cp hello.txt s3://acloudguru2019-ccp

## Config and Credentials on EC2
- cd ~/.aws
- nano credentials : this has the credentials in plain text
- aws configure >> put bad information in it
- aws s3 ls will not work now

## Exam Tips
- you can interact with console, command line interface or software dev kits (programming language to interact with env)

## Using Roles
#### In terminal
- ssh to ec2 again
- sudo su
- aws s3 ls >> this fails because we gave it bogus credentials last time
- cd ~/
- rm -rf .aws
- now this will try to connect using the role
- if hacked it would have admin access to s3 using this instance not admin access to the entire aws environment

## Exam Tips
- roles more secure than using access keys
- easier to manage
- can apply roles to ec2 instances at any time and takes affect immediately
- roles are universal no need to specify a region they work in all of them
