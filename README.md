# Amazon Simple Storage Service Single account or cross account automation using AWS CloudFormation

Use this [AWS CloudFormation](https://raw.githubusercontent.com/prachikhanna84/AmazonSimpleStorageServiceCopyAutomation/main/AmazonS3Copy.yaml) template to create the complete infrastructure to copy contents from source Amazon S3 provided by the user to target Amazon S3 bucket created in user account. 

![Amazon S3 Copy Automation Architecture](https://github.com/prachikhanna84/AmazonSimpleStorageServiceCopyAutomation/blob/main/docs/Amazon%20S3%20Copy%20Augtomation.jpg)

## Resources created by cloudformation

- Target Amazon S3 bucket
- AWS Identity and Access Management (IAM) role for AWS Lambda to access/put objects in the target Amazon S3 bucket
- AWS Lambda function to copy the contents from source to target bucket 
- Amazon CloudWatch log for AWS Lambda function log tracking
- CloudFormation custom resource to trigger the AWS Lambda

## Pre-requisites to use this CloudFormation template

- AWS Account 
- Source Amazon S3 bucket 
- access to execute the CloudFormation template

## how to use the CloudFormation

- execute the CloudFormation template in AWS account
- all the resources mention will be created by CloudFormation template 
- object from source bucket will be copied

## Debugging

- AWS Lambda logs are published in CloudWatch logs

## Contributing
Contributions are more than welcome. This project has adopted the [Amazon Open Source Code of Conduct](https://aws.github.io/code-of-conduct). For more information see the [Code of Conduct FAQ](https://aws.github.io/code-of-conduct-faq) or contact opensource-codeofconduct@amazon.com with any additional questions or comments.

## License
This library is licensed under the MIT-0 License. See the [LICENSE file](https://raw.githubusercontent.com/prachikhanna84/AmazonSimpleStorageServiceCopyAutomation/main/LICENSE.md).
