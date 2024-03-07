# Creating an S3 Bucket & Creating an Static S3 Website

## Notes about S3
- S3 Buckets are global
- buckets are always a web address
- bucket is a folder name
- by default the files are not public
- you can change the storage class in the properties of the file
- Advanced settings -> Transfer Acceleration and you can test the speed to upload files to different regions around the world

## Exam Tips
- view bucket globally but can have buckets in individual region. You choose a region when you create the bucket. Can do cross region replication.
- Can change storage class and encryption on the fly
- Remember the 6 storage classes
- Transfer acceleration uses edge locations and caches content to make access faster
- Restricting bucket access 1) bucket policies 2) object policies 3) IAM policies to users and groups

## Creating a static S3 Website
- you can make all objects in bucket public by default
- you can use bucket to host website in properties -> Static Website Hosting and select the files that it should use for the index and the error

## Exam Tips
- you can use bucket policies that make entire s3 buckets public
- can use s3 to host static websites
- s3 scales automatically to meet demands