
- ## AWS: API, Dynamo and Lambda .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305203/submit)
   - ### AWS API Gateway Overview
      1. #### What is Amazon API Gateway?
         -  a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic.
      2. #### Why is Amazon API Gateway an important part of the Serverless ecosystem?
         -  the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups
      3. #### How does API Gateway integrate with other AWS services?
         - API Gateway supports direct integrations that can be configured in the API Gateway user interface (or via the API Gateway’s own API) for the following actions:
   - ### AWS API Gateway
      1. #### What are the some benefits of using Amazon API Gateway?
         - Efficient API development, Performance at any scale, Cost savings at scale, Easy monitoring
      2. #### What two API types might you choose from?
         - Amazon cloudWatch , API Gateaway cachw
   - ### AWS DynamoDB Guide
      1. #### What is DynamoDB?
         -  a hosted NoSQL database offered by Amazon Web Services (AWS)
      2. #### Under what circumstances would you recommend DynamoDB over MongoDB?
            - Applications with large amounts of data and strict latency requirements
            - Serverless applications using AWS Lambda
            - Data sets with simple, known access patterns.
   - ### AWS DynamoDB
      1. #### Explain to a non-technical friend how DynamoDB works.
         - It is a secure server that will help you getting database without server and its complications
   - ### Dynamoose
      1. #### What is Dynamoose?
         - a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar.
      2. #### What are some key features of Dynamoose?
         - Strict data modeling (validation, required attributes, and more)
         - Ability to transform data before saving or retrieving items
         - DynamoDB Single Table Design Support
         - Easy to use syntax
         - High level API
         - Type safety
