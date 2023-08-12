# AWS CLOUDFORMATION COURSE

This repo contains different labs which on each of them will appoint to create different IaC using  the service provided by AWS.

## Lab 1

It creates a DynamoDB table

## Stacks (Non nested)

Shows how a stack is created using a template, in this example through all the steps some resources in AWS are created, such as:
- Lambda function
- Role for the Lambda function
- Policies applied to the role
- API
- DynamoDB table

You may also notice that a filed name interface is used, it is used when you are trying to deploy the template, you will see the different parameters organized and also those where you have to pick only one option such  the environment for lambda.