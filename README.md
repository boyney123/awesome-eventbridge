<p align="center">
  <img src="https://user-images.githubusercontent.com/3268013/149550617-d92fa8ff-f95d-499c-8515-0ed0be976fbf.png" height="200px">
</p>

# Awesome EventBridge 🚀

A handy list of resources for getting up to speed on events, patterns, and using [Amazon EventBridge](https://aws.amazon.com/eventbridge/).

Contributions welcome!

_Inspired by [Awesome DynamoDB](https://github.com/alexdebrie/awesome-dynamodb)_

## Table of Contents

- [Videos](#videos)
- [Written resources](#written-resources)
- [Tools](#tools)

## Videos

- [How to get started with Amazon EventBridge](https://www.youtube.com/watch?v=ea9SCYDJIm4). James Beswick talks us through a quick introduction into EventBridge.

- AWS re:Invent 2020: [Building event-driven applications with Amazon EventBridge](https://www.youtube.com/watch?v=Wk0FoXTUEjo). Great talk by Stephen Liedig around EventBridge, Multi-account patterns and recommended practices. 

- AWS re:Invent 2021: [Using events and workflows to build distributed applications](https://www.youtube.com/watch?v=wS7F__gEqx4). Great talk around events and workflows using AWS. Diving into Events, Workflows, Orchestration, Choreography, EventBridge and Step functions.

- [Accelerate Your Serverless Adoption with Amazon EventBridge](https://www.youtube.com/watch?v=sTZpoSGOSOI). Sheen Brisals shows us how LEGO are using Serverless and EventBridge inside their serverless architecture. Great watch.

- [Schema Registry, DLQ, Retry Policy with demos](https://www.youtube.com/watch?v=-R8SpbCYMY0). Really good video into some core features of EventBridge and some demos around DLQ and Retry policies.

- [EventBridge quick learning videos](https://www.youtube.com/playlist?list=PLWVS7QXuxjVkflYnCmLzZO_1q0UU0xD08). James Beswick gives us some great quick videos to learn about Amazon Eventbridge.

- [Event-Driven Architecture at PostNL Scale](https://www.youtube.com/watch?v=nyoMF1AEI7g). Luc van Donkersgoed gives us some great insight into how to scale EventBridge with some interesting patterns like Authenticating producers/consumers, getting around EventBridge payload limits, EventBridge Metrics and much more...

- [The Art of Microservices Communication with AWS EventBridge](https://www.youtube.com/watch?v=0gPZx9ex9gY). Sheen Brisals gives another amazing talk on EventBridge and various different patterns we can explore. A great watch with many learnings to take away from it.


- [Serverlesspresso - A demo using EventBridge, Step Functions and more!](https://www.youtube.com/watch?v=71ln5qjiVbk). James Beswick talks us through how the Serverlesspresso application was created with a mixture of API Gateway, IOT Core and EventBridge that glues the whole thing together.

## Written resources

- [EventBridge Storming](https://medium.com/serverless-transformation/eventbridge-storming-how-to-build-state-of-the-art-event-driven-serverless-architectures-e07270d4dee) and [Finding a Loosely Coupled Utopia with Event-Driven Serverless](https://medium.com/serverless-transformation/service-ports-finding-a-loosely-coupled-utopia-with-event-driven-serverless-6964aacd1487). Ben Ellerby gives us a fantastic piece about EventBridge and [EventStorming](https://www.eventstorming.com/). Talking about DDD, Bounded Context and much more.

- [Archive & Replay Events In Tandem With A Circuit-Breaker](https://medium.com/lego-engineering/amazon-eventbridge-archive-replay-events-in-tandem-with-a-circuit-breaker-c049a4c6857f). Here we understand patterns around Archiving, Replaying and Circuit breaking with EventBridge. Full of examples and diagrams to help us understand.

- [A Case for Event Batching in Amazon EventBridge](https://betterprogramming.pub/a-case-for-event-batching-in-amazon-eventbridge-303f5c3eecee). Understand event payloads, and batching. Using EventBridge to batch up events with the detail in order to process them.

- [Amazon EventBridge: API Destinations Demystified-Part I](https://medium.com/lego-engineering/amazon-eventbridge-api-destinations-demystified-part-i-23fa70d9a04d) and [Part 2](https://medium.com/lego-engineering/amazon-eventbridge-how-to-manage-api-connection-credentials-with-aws-secrets-manager-f773f7d2aac5). Learn the power of API destinations for EventBridge. Filled with tutorial, examples and great explanations.

- [A fishing analogy for EventBridge filtering rules](https://medium.com/lego-engineering/a-fishing-analogy-for-eventbridge-filtering-rules-e2378d2fda90). A great analogy to help us understand how filtering with EventBridge works.

- [How to Observe EventBridge Events with Postman and WebSockets](https://www.boyney.io/blog/2021-09-06-debug-eventbridge-with-postman). Learn how to use WebSockets with EventBridge to take a look inside your bus and debug.

- [Serverless patterns with EventBridge](https://serverlessland.com/patterns?services=eventbridge). A wide range of Serverless patterns (SAM, CDK) for EventBridge.

- [Use Amazon S3 Event Notifications with Amazon EventBridge](https://aws.amazon.com/blogs/aws/new-use-amazon-s3-event-notifications-with-amazon-eventbridge/) - Guide to understand how to quickly and efficiently react to changes in your S3 Objects.

- [Amazon EventBridge: Event Payload Standards](https://www.boyney.io/blog/2022-02-11-event-payload-patterns) - Explore ideas behind standardising your event payloads for Amazon EventBridge and explore what other people are doing.


## Tools

- [evb-cli](https://github.com/mhlabs/evb-cli) - Pattern generator and debugging tool for Amazon EventBridge. Browser targets of events, generate diagrams, generate code bindings and much more. All from the CLI.

- [EventCatalog](https://www.eventcatalog.dev/) - Document your Event Architectures using Markdown files. Use the [Amazon EventBridge](https://www.eventcatalog.dev/docs/api/plugins/@eventcatalog/plugin-doc-generator-amazon-eventbridge) plugin to generate docs from your Schema Registry. Visualise targets, rules and much more...

- [cdk-eventbridge-socket](https://github.com/boyney123/cdk-eventbridge-socket) - CDK construct that creates a WebSocket endpoint for you for any EventBridge rule you are interested in. (Built for debugging + testing )

- [sls-dev-tools](https://github.com/Theodo-UK/sls-dev-tools#eventbridge) - Dev Tools for the Serverless World. Another great CLI tool for serverless support and EventBridge!

- [EventBridge Atlas](https://github.com/boyney123/eventbridge-atlas) - Document, Discover and Share Amazon EventBridge Schemas. Transforms your schemas into documentation.

- [EventBridge Canon](https://github.com/boyney123/eventbridge-canon) - Simple UI to Publish, Save and Share AWS EventBridge Events. Think Postman but for EventBridge.

- [sls-test-tools](https://github.com/Theodo-UK/sls-test-tools) - Custom Jest Assertions for Serverless integration testing. Test your EventBridge integration with these awesome jest tools. Check if events are raised and the payloads of them.

- [serverless-offline-eventbridge](https://github.com/rubenkaiser/serverless-offline-eventBridge) -  serverless offline plugin that enables eventBridge events 

- [Typebridge](https://github.com/fredericbarthelet/typebridge) - TypeScript toolbox for EventBridge. 
