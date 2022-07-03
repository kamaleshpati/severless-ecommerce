# Serverless Event-driven E-commerce Microservices

This is a Serverless Event-driven E-commerce project for TypeScript development with CDK.
The `cdk.json` file tells the CDK Toolkit how to execute  app.

### Check Explanation of this Repository
* [AWS Event-driven Serverless Microservices using AWS Lambda, API Gateway, EventBridge, SQS, DynamoDB and CDK for IaC](https://mehmetozkaya.medium.com/aws-event-driven-serverless-microservices-using-aws-lambda-api-gateway-eventbridge-sqs-dynamodb-a7f46220b738)
* [See All Articles - AWS Serverless Microservices with Patterns & Best Practices](https://medium.com/aws-serverless-microservices-with-patterns-best)
* mehmetozkaya](https://github.com/mehmetozkaya

## Whats Including In This Repository
We will be following the reference architecture above which is a real-world **Serverless E-commerce application** and it includes;

* **REST API** and **CRUD** endpoints with using **AWS Lambda, API Gateway**
* **Data persistence** with using **AWS DynamoDB**
* **Decouple microservices** with events using **Amazon EventBridge**
* **Message Queues** for cross-service communication using **AWS SQS**
* **Cloud stack development** with **IaC** using **AWS CloudFormation and AWS CDK**

* **Product API -> https://xxx.execute-api.ap-southeast-1.amazonaws.com/prod/product**
* **Basket API -> https://xxx.execute-api.ap-southeast-1.amazonaws.com/prod/basket**
* **Ordering API -> https://xxx.execute-api.ap-southeast-1.amazonaws.com/prod/order**

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template

