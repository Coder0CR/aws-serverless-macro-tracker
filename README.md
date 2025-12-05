# Serverless Macro Tracker Portfolio
RESTful API that allows a user to log their meals for the day

## Architecture
User->API Gateway->Lambda->Step Functions->DynamoDB<br/>
DevOps Flow

## Features and Goals
* RESTful API for Meal Logging
* Asynchronous Macro Analysis
* Automated DevSecOps Pipeline

## Technology Stack
* AWS CDK 2.0
* TypeScript
* AWS API Gateway
* AWS Lambda
* AWS DynamoDB
* AWS Step Functions
* AWS CodePipeline
* Checkov

## How to Deploy
> [!WARNING]
> Deploying this to your AWS account may result in charges to your AWS account.
``` bash
git clone
```
``` bash
npm install
```
``` bash
cdk deploy
```
