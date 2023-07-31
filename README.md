# AWS Cloud Resume Challenge

This is my attempt at cloud resume challenge in AWS. [The Cloud Resume Challenge](https://cloudresumechallenge.dev) is a multiple-step resume project which helps build and demonstrate skills fundamental to pursuing a career in Cloud. The project was published by Forrest Brazeal.

## Architecture

## Services Used

* **S3:** The files are hosted in an S3 bucket.

* **AWS CloudFront:** CloudFront is used as the CDN.

* **Route53:** The domain is hosted and configured in AWS Route53

* **AWS Lambda:** The python function to count and store views in DynamoDB uses Lambda

* **DynamoDB:** The view count is stored in DynamoDB

* **Github Actions:** All updates and changes are pushed with Github commands in the CLI


