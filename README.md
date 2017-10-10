# kms-encryption-demo
A simple demo that shows how KMS can be used from Lambda to encrypt data before storing in a DynamoDB table.


This repository consists of a single CloudFormation template that builds the following resources:

1) A KMS Key
2) A IAM Role for Lambda to use
3) A DynamoDB table
4) A Lambda function to demonstrate encryption with KMS and storage of encrypted value in DynamoDB.
