# S3Copy

Use this cloudformation template to create the complete infrastructure to copy contents from source S3 provided by the user to target S3 bucket created in user account. 

## Resources created by cloudformation

- Target S3 bucket
- IAM role for Lambda to access/put objects in the target S3 bucket
- Lambda function to copy the contents from source to target bucket 
- Cloud watch log for Lambda function log tracking
- Cloudformation custom resource to trigger the Lambda
