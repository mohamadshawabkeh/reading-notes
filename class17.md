# AWS: S3 and Lambda 

## AWS S3

#### What is Amazon S3?
Amazon S3 (Simple Storage Service) is a cloud-based object storage service provided by Amazon Web Services (AWS). It is designed to store and retrieve any amount of data from anywhere on the web, offering durability, scalability, security, and performance.

#### Use Cases for Amazon S3
- **Data Backup and Recovery**: S3 can be used to store backup copies of data, ensuring data durability and availability.
- **Website Hosting**: S3 can host static websites, allowing users to store and serve HTML, CSS, JavaScript, and other web assets.
- **Data Archiving**: S3 provides long-term storage for infrequently accessed data, serving as a cost-effective solution for archiving.
- **Data Lakes**: S3 is commonly used as a storage layer for building data lakes, where large amounts of structured and unstructured data can be stored and analyzed.
- **Content Distribution**: S3 can be integrated with content delivery networks (CDNs) to distribute and deliver content globally with low latency.

#### Benefits of using Amazon S3
- **Scalability**: S3 can store an unlimited amount of data, scaling seamlessly to accommodate any workload.
- **Durability**: S3 automatically replicates data across multiple locations, ensuring high durability and availability.
- **Security**: S3 offers multiple security features, including encryption at rest and in transit, access control policies, and integration with AWS Identity and Access Management (IAM).
- **Performance**: S3 is optimized for high-speed data retrieval and can handle high levels of concurrent read and write requests.
- **Cost-Effectiveness**: S3 offers flexible pricing options, pay-as-you-go billing, and cost optimization tools to help users manage storage costs effectively.

## AWS Lambda Basics

#### What is AWS Lambda?
AWS Lambda is a serverless compute service provided by AWS. It allows users to run their code without provisioning or managing servers. With Lambda, users can upload their code and configure triggers to execute the code in response to events, such as changes in data, file uploads, or API calls.

#### Use Cases for AWS Lambdas
- **Microservices**: Lambdas are commonly used to build microservices architectures, where each Lambda function performs a specific task within a larger application.
- **Event Processing**: Lambdas can process events from various AWS services, such as S3, DynamoDB, and Amazon Kinesis, enabling real-time data processing and analysis.
- **Web Application Backend**: Lambdas can serve as the backend for web applications, handling API requests and executing business logic.
- **Data Transformations**: Lambdas can be used to transform and manipulate data before storing it in databases or other storage systems.
- **Scheduled Tasks**: Lambdas can be triggered by scheduled events using AWS CloudWatch Events, allowing users to automate repetitive tasks.

#### "Serverless" in Non-technical Terms
Imagine you have a personal assistant who performs tasks for you without you needing to hire and manage them directly. In a similar way, serverless computing, like AWS Lambda, allows developers to write code and run it without worrying about the underlying infrastructure, such as servers. It eliminates the need to provision, manage, or scale servers, making development easier and more efficient.

## CDN

## What is a CDN?
A CDN (Content Delivery Network) is a distributed network of servers located in different geographical locations worldwide. It works as a middle layer between a website's origin server and the end user, caching and delivering website content from the server closest to the user's location.

#### How does a CDN work with relation to the website visitor?
When a website visitor requests content, such as images, videos, or static files, the CDN routes the request to the nearest server in its network. This server delivers the content to the visitor, minimizing latency and reducing the load on the website's origin server. By caching and delivering content from servers closer to the user, a CDN improves the website's performance and provides a better user experience.

#### Benefits of employing a CDN
- **Improved Performance**: By serving content from servers closer to the user, a CDN reduces latency and improves website loading speed.
- **Scalability**: CDNs can handle high traffic loads and distribute the load across multiple servers, ensuring website performance during peak periods.
- **Global Reach**: CDNs have servers located in various regions worldwide, enabling fast content delivery to users across the globe.
- **Reduced Bandwidth Costs**: CDNs help reduce bandwidth usage and associated costs by caching and delivering content more efficiently.
- **Enhanced Security**: CDNs offer security features such as DDoS protection, SSL/TLS encryption, and web application firewalls, helping protect websites from malicious attacks.


### return to [Main Read Me File](./README.md)