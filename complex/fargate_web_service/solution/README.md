# Serverless Microservice on AWS Fargate Issues

## 👍 Solution

1. The ALB Security Group Points to VPC Default SG
1. ALB Health check is being done for `HTTPS` protocol
1. The Security Group for the Fargate is set for `UDP` and port??
1. IAM Permissions for Log is missing for the Task Role
