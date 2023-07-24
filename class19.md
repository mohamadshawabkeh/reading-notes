# AWS: API, Dynamo, and Lambda

## AWS API Gateway Overview

**What is Amazon API Gateway?**
Amazon API Gateway is a fully managed service provided by AWS that makes it easy for developers to create, publish, maintain, monitor, and secure APIs (Application Programming Interfaces) at any scale. It acts as a front-door for applications to access data, business logic, or functionality from backend services, servers, or AWS Lambda functions.

**Why is Amazon API Gateway an important part of the Serverless ecosystem?**
Amazon API Gateway plays a crucial role in the Serverless ecosystem because it enables developers to expose serverless functions, such as AWS Lambda functions, to the outside world via APIs. It acts as a bridge between client applications and serverless functions, providing a serverless architecture that scales automatically and only charges based on actual usage.

**How does API Gateway integrate with other AWS services?**
API Gateway integrates seamlessly with various AWS services. Some key integrations include:

1. **AWS Lambda**: API Gateway can directly invoke AWS Lambda functions, allowing serverless execution of business logic in response to API requests.

2. **AWS Cognito**: It supports Cognito user pools for authentication and authorization, making it easy to secure APIs.

3. **AWS IAM**: API Gateway leverages IAM roles to control access to APIs and AWS resources.

4. **AWS S3**: API Gateway can be used to trigger S3 events, allowing you to perform actions on objects in S3 buckets.

## AWS API Gateway

**What are some benefits of using Amazon API Gateway?**
Some benefits of using Amazon API Gateway include:

1. **Scalability**: API Gateway automatically scales to handle varying levels of traffic, ensuring high availability and performance.

2. **Security**: It provides built-in security features like authentication, authorization, and access control to protect APIs and resources.

3. **Caching**: API Gateway supports caching responses, reducing the load on backend services and improving API performance.

4. **Monitoring and Analytics**: It offers detailed monitoring, logging, and analytics to track API usage and identify potential issues.

**What two API types might you choose from?**
Amazon API Gateway offers two main types of APIs:

1. **REST APIs**: Representational State Transfer (REST) APIs follow RESTful principles and use HTTP methods like GET, POST, PUT, DELETE to interact with resources.

2. **WebSocket APIs**: WebSocket APIs enable real-time two-way communication between clients and servers, suitable for applications that require low-latency and bi-directional data flow.

## AWS DynamoDB Guide

**What is DynamoDB?**
Amazon DynamoDB is a fully managed NoSQL database service provided by AWS. It offers reliable performance, seamless scalability, and automatic replication across multiple regions, making it ideal for applications with high read and write requirements.

**Under what circumstances would you recommend DynamoDB over MongoDB?**
DynamoDB might be recommended over MongoDB in scenarios where:

1. **Predictable Performance**: DynamoDB provides consistent and predictable performance regardless of data volume, whereas MongoDB's performance can vary based on the cluster configuration and query patterns.

2. **Fully Managed Service**: DynamoDB is fully managed by AWS, which simplifies administrative tasks, while MongoDB often requires more operational overhead.

3. **Scalability**: DynamoDB offers seamless and automatic scaling with no capacity planning, making it suitable for rapidly growing applications.

## AWS DynamoDB

**Explain to a non-technical friend how DynamoDB works.**
DynamoDB is like a huge, organized, and super-fast filing cabinet for data in the digital world. It stores information in a structured way so that we can easily find and retrieve it whenever we need it. The best part is that it can handle lots of people accessing the data at the same time without getting slow or messy.

## Dynamoose

**What is Dynamoose?**
Dynamoose is a modeling tool and ODM (Object Data Mapping) library for Amazon DynamoDB, designed to simplify the interaction with DynamoDB and make it easier for developers to work with data in their applications.

**What are some key features of Dynamoose?**
Some key features of Dynamoose include:

1. **Schema Definition**: Dynamoose allows you to define a schema for your data, which helps ensure that the data is consistent and follows a specific structure.

2. **CRUD Operations**: It provides easy-to-use methods for performing Create, Read, Update, and Delete operations on DynamoDB items.

3. **Middleware Support**: Dynamoose supports middleware, allowing you to perform actions before or after specific operations, making it convenient for handling data transformations and validations.

4. **Promise-based API**: It offers a promise-based API for working with DynamoDB, making asynchronous programming simpler and more manageable.


### return to [Main Read Me File](./README.md)