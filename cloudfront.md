# CloudFront
## What is it?
- Amazon's content delivery network that deliver content to a user
- Used to deliver entire website
- Requests for content automatically routed to the closest edge location

## Terminology
Edge locations - where the content is cached. Separate to a region or availability zone
Origin - the origin of the files that the cdn will distribute
Distribution - name of the CDN (collection of edge locations)

## How it works
Users query edge location
Edge locations have to connect to origin and download the file at the edge location
When a second user comes in, the file is already cached at the edge location
File has a TTL (time to live)

## Types
1. Web distribution
2. RTMP

## Setting up CloudFront
- Most people choose web
- Choose s3 bucket
- Can restrict access to bucket
- Choose defaults
- Create

## To use:
Copy CloudFront distribution/file in the bucket
If you refresh it will show up instantaneously

## Exam Tips
- Remember terminology: edge locations, origin, distribution (name of CDN)
- Types of distributions: web and RTMP for Adobe
- Edge locations are not read only you can write to them too to put an object in them
- Object are cached for life of TTL which is in seconds
- You can clear it out, but you will be charged for it