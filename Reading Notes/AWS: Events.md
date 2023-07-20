AWS: Events

- ## AWS: Events .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305202/submit)
   - ### AWS SQS vs SNS
      1. #### What is the difference betweeen SQS and SNS?
         - Amazon SNS (Simple Notification Service): Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients.
         - Amazon SQS (Simple Queue Service): Amazon SQS is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless app
      2. #### What are some use cases for both SNS and SQS?
         - Choose SNS if:
           - You would like to be able to publish and consume batches of messages.
           - You would like to allow same message to be processed in multiple ways.
           - Multiple subscribers are needed.
         - Choose SQS if:
           - You need a simple queue with no particular additional requirements.
           - Decoupling two applications and allowing parallel asynchronous processing.
           - Only one subscriber is needed.
 
   - ### AWS SNS and SQS
      1. #### Describe how to use SQS and SNS in a “fanout” pattern.
         - Create an SNS Topic. then Subscribe SQS Queues to the SNS Topic After that Publish to the SNS Topic. Now you can receive Messages in subscribed SQS queues.
      2. #### Explain how “push notifications” work, using SNS.
         - it works on mobile app by creating a SNS application then obtain tokens from devices, after that you can send notifications to other devoce
