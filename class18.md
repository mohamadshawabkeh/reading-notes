# AWS: Events


## AWS SQS vs. SNS


#### What is the difference between SQS and SNS?

- **SQS** is a message queuing service for reliable communication between components using queues.
- **SNS** is a pub/sub messaging service for broadcasting messages to multiple subscribers.

#### What are some use cases for both SNS and SQS?

**SQS Use cases**:
- Task Queues
- Decoupling Applications
- Buffering
- Reliable Messaging

**SNS Use cases**:
- Real-time Notifications
- Fanout Pattern
- Mobile Push Notifications

## AWS SNS and SQS

#### Describe how to use SQS and SNS in a "fanout" pattern.

1. Create an SNS Topic.
2. Subscribe SQS Queues to the SNS Topic.
3. Publish to the SNS Topic.
4. Receive Messages in subscribed SQS queues.

#### Explain how "push notifications" work, using SNS.

1. Set Up Mobile Platforms and register your mobile app with push notification services.
2. Create an SNS Platform Application for each mobile platform.
3. Obtain Device Tokens when users install the mobile app.
4. Register Device Tokens with SNS.
5. Publish Notifications to the SNS platform application.

## SQS and SNS Basics

#### How might a large-scale, distributed application make use of a Queue system like SQS?

1. Load Leveling: Decouple components to balance traffic during spikes.
2. Fault Tolerance: Ensure message persistence and reprocessing on failure.
3. Asynchronous Processing: Enable non-blocking communication between components.
4. Scalability: Automatically scale based on demand.
5. Microservices Architecture: Facilitate communication between microservices.
6. Distributed Processing: Improve application performance by distributing tasks.

### return to [Main Read Me File](./README.md)