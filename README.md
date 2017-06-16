brianmuse.com
=============

A very simple and surely underwhelming website about me. See it at [brianmuse.com](http://brianmuse.com)


## Deployment

This app is deployed to AWS using S3, CloudFront and Route53

- Domain is registered with GoDaddy.com
- DNS is hosted in route53
- Files are hosted on S3
- DNS points to and is served through CloudFront

S3 contains two buckets:
- www.brianmuse.com
- brianmuse.com

The former is configured to redirect to `https://brianmuse.com`
The latter contains the project files.

## References

- https://aws.amazon.com/getting-started/projects/host-static-website/
- https://medium.com/@willmorgan/moving-a-static-website-to-aws-s3-cloudfront-with-https-1fdd95563106