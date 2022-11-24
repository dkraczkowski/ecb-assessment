# Description

Your assessment is to design and build a currency exchange tracking application in the AWS lambda environment.

The application should rely on [European Central Bank Data](https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.en.html). 

Exchange rates should be fetched every day and stored in a database. 

The application should expose a public REST API endpoint that provides current exchange rate information for all tracked currencies and their change compared to the previous day for all the tracked currencies. 

## Business Requirements

- As an API Client, I want to see current exchange rates.

- As an API Client, I want to understand how the exchange rate has changed compared to the previous day. 


## Technical Requirements

- The application should be written in python 3.9
- The application can only use the following AWS Services:
  - AWS Lambda
  - AWS CloudFormation
  - AWS SQS
  - AWS SNS
  - AWS Cloudwatch
  - AWS API Gateway
  - AWS S3
  - AWS DynamoDB
  - AWS Log Insights

- Delivered code and documentation SHOULD follow the best practices
- Application must be fully functioning
- Application must be deployable (either to AWS or [localstack](https://docs.localstack.cloud/) )

You can use cloudformation, CDK, serverless or AWS CLI for the deployment.

