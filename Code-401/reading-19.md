# AWS Events

[AWS SQS VS. SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

What is the difference betweeen SQS and SNS?

- Simple queue service versus simple notification service. Both are used in -ible cloud-based applications. SQS is a queue service (seems self-descriptive) while SNS is a publish-subscribe service/push notification service.

What are some use cases for both SNS and SQS?

- Use cases for SNS: News apps, Social media apps, apps that require or use notifications, email services. Apps where multiple subscribers are needed.

- Use cases for SQS: Where only one subscriber is needed, no additional requirements to the queue.

[AWS SNS AND SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

Describe how to use SQS and SNS in a “fanout” pattern.

- This is when asynchronous processing occurs after a message is published with SNS and replicated/pushed to SQS among other services.

Explain how “push notifications” work, using SNS.

- SNS uses a device token to create a mobile endpoint to which it will push notifications to.

[SQS AND SNS BASICS](https://www.youtube.com/watch?v=UesxWuZMZqI)

How might a large scale, distributed application make use of a Queue system like SQS?

- SQS gives you the ability to scale as your traffic grows. You can expect the same level of performance from the queue. A certain level of elasticity. SQS also allows you to process messages as soon as they arrive in the queue.

## To bookmark and review

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)