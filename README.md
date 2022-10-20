# S3Copy

Use this cloudformation template to create the complete infrastructure to copy contents from source S3 provided by the user to target S3 bucket created in user account. 

## Resources created by cloudformation

- Target S3 bucket
- IAM role for Lambda to access/put objects in the target S3 bucket
- Lambda function to copy the contents from source to target bucket 
- Cloud watch log for Lambda function log tracking
- Cloudformation custom resource to trigger the Lambda

## Pre-requisites to use this cloudformation template

- AWS Account 
- Source S3 bucket 
- access to execute the cloudformation template

## how to use the cloudformation

### execute the cloudformation template in AWS account
### all the resources mention will be created by cloudformation template 
### object from source bucket will be copied

## Debugging

### Lambda logs are published in Cloudwatch logs
