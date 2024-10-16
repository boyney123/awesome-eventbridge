<p align="center">
  <img src="https://user-images.githubusercontent.com/3268013/149550617-d92fa8ff-f95d-499c-8515-0ed0be976fbf.png" height="200px">
</p>

# Awesome EventBridge 🚀

A handy list of resources for getting up to speed on events, patterns, and using [Amazon EventBridge](https://aws.amazon.com/eventbridge/).

Contributions welcome!

## Similar Lists

[Awesome DynamoDB](https://github.com/alexdebrie/awesome-dynamodb) - List of resources for learning about modeling, operating, and using Amazon DynamoDB

[Awesome Event Patterns](https://github.com/boyney123/awesome-event-patterns) - Collection of links, videos and things to help with event architecture event patterns.

## Table of Contents

- [Videos](#videos)
- [Written resources](#written-resources)
- [Tools](#tools)
- [Example Projects](#example-projects)

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

- [Best practices to design your events in event-driven applications](https://www.youtube.com/watch?v=uPljZ08sk2c). David Boyne goes through Event Design patterns with EventBridge looking into Nofitication and State Carried patterns, the tradeoffs and ways to improve your event design by thinking Event first design.

- [User-driven Composable Infrastructure with CDK, Step Functions and CodeBuild](https://www.youtube.com/watch?v=bLJ2A5YXDTY). Luc van Donkersgoed gives us great insight into how PostNL are using CDK to automate deployments with producers and consumers with self service systems.

- [20 ways event-driven architectures can improve your development process](https://www.youtube.com/watch?v=jrYF-W8WCcQ) - James Beswick gives us a fun talk about how EDA can improve our development workflows and processes.

- [AWS re:Invent 2022 - Designing event-driven integrations using Amazon EventBridge](https://www.youtube.com/watch?v=W3Rh70jG-LM) - Stephen Liedig is back with his 2022 re:invent talk. Dives into event bus topologies, producer / consumer responsibilities, event standards, idempotency and much more. If you want to dive into EventBridge this talk is for you!

- [What is EventBridge Pipes and EventBridge Scheduler?](https://www.youtube.com/watch?v=I8KDerQ9BRU) - Luc van Donkersgoed gives us a 10 minute summary of Pipes and Scheduler with some example usecases. If you want to start learning about pipes or scheduler, spare 10 minutes and give this a watch!

- [Advanced Event-driven Architectures at the LEGO Group](https://www.youtube.com/watch?v=6_Yzybhmj-8&t=236s) - [Sarah Hamilton](https://twitter.com/serverlesssarah) gives us a great talk on how Lego are using event-driven architecture, diving into event streams, pub/sub with EventBridge, passing events through APIS (API Destinations) and finishing with Step Functions. One to watch for some inspiration!

- [EDA in Practice: Building an eCommerce Platform at Cinch • Emily Shea & Toli Apostolidis](https://www.youtube.com/watch?v=wM-dTroS0FA&t=2077s) - [Emily Shea](https://twitter.com/em__shea) and [Toli Apostolidis](https://twitter.com/apostolis09) give us a great talk on event-driven architecture at [cinch](https://cinch.co.uk/). How they developed platform in 6 months and what event driven patterns emerged over time. Also some extras around how they use domain driven design, contract testing and how they scale their services in their org. Worth watching!

- [Understanding application integration with EventBridge Pipes](https://www.youtube.com/watch?v=9Pf4E1ZZr08&t=989s) - Eric Johnson gives us a dive into EventBridge pipes, usecases and why you may want to use them.

- [The Tao of Event-Driven Architectures](https://www.youtube.com/watch?v=9r9WDzzTcr0) - Luc van Donkersgoed gives us another great talk where he talks about 10 rules when building event-driven architectures. Goes into schemas, storage first patterns, observability, event design and much more!

- [Advanced event-driven patterns with Amazon EventBridge reInvent:2023](https://www.youtube.com/watch?v=6X4lSPkn4ps&t=8s) - AWS Hero Sheen Brisals is back again at re:Invent 2023 to give us all a great talk about event-driven patterns with EventBridge. If you want to dive deeper into patterns then this talk is for you!

- [Refactoring to Serverless re:Invent 2023](https://www.youtube.com/watch?v=bIu8XZZROw4&t=2668s) - Great talk here by Gregor Hohpe and Sindhu Pillai talking about serverless refactorings. Many examples of EventBridge and EventBridge Pipes mentioned in this talk.

- [Navigating the journey to serverless event-driven architecture](https://www.youtube.com/watch?v=hvGuqHp051c) - Talk by David Boyne to help you understand how you should navigate and build a serverless event-driven architecture, where you should start, how domain driven design can help, and how AWS services (including EventBridge) can help you get there.

- [Advanced integration patterns & trade-offs for loosely coupled systems re:Invent 2023](https://www.youtube.com/watch?v=FGKGdUiZKto) - Talk by Dirk Forhner and Gregor Hohpe at re:Invent 2023. Great talk diving deep into integration patterns, coupling, message channels and much more. Useful to know if you are using Amazon EventBridge!

- **Integration EventBridge with AppSync (New in 2024)** - EventBridge added [support for AppSync](https://aws.amazon.com/about-aws/whats-new/2023/04/aws-appsync-publishing-events-amazon-eventbridge/) in Jan 2024. This allows you to use AppSync as a target of your events, meaning your clients can listen to your server events. Focus Otter covers it in his [YouTube video](https://www.youtube.com/watch?v=XccNLyZutbU), Josh Kahn covers it in [blog post](https://aws.amazon.com/blogs/mobile/invoke-aws-services-directly-from-aws-appsync/) and [ServerlessLand has a pattern for you](https://serverlessland.com/patterns/eventbridge-to-appsync-sam) to get started.

- [Empowering Architectural Evolution: Governing Event-Driven Solutions](https://www.youtube.com/watch?v=-Pv_kYflEEg) - This is a fantastic talk from Sam Dengler. Not really aimed directly at EventBridge, but covers some many tips and thoughts around EDA governance that you can apply to your event-driven architectures using EventBridge. 100% worth checking out.

- [EventBridge Under the hood](https://www.youtube.com/watch?v=t1UfgCE02Do) - Join Nick Smit (Principle Product Manager of EventBridge), Julian Wood and Rishi Baldawa (Pricinple Engineer on EventBridge) dive into EventBridge, how it works and refactors they made along the way. If you want to know the details of EventBridge then this video is for you!

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

- [Testing Amazon EventBridge events using AWS Step Functions](https://aws.amazon.com/de/blogs/compute/testing-amazon-eventbridge-events-using-aws-step-functions/) - Explore how you can use Step Functions to help test your EDA with EventBridge.

- [How to use EventBridge as a Cross-Account Event Backbone](https://dev.to/eoinsha/how-to-use-eventbridge-as-a-cross-account-event-backbone-5fik) - A  post by [Eoin Shanaghy](https://twitter.com/eoins) explaining how we can utilise EventBridge and share events cross accounts. Worth a read if you are using multiple AWS accounts and want to share events between them.

- [Sending Amazon EventBridge events to private endpoints in a VPC](https://aws.amazon.com/blogs/compute/sending-amazon-eventbridge-events-to-private-endpoints-in-a-vpc/) - A great blog post by Emily Shea explaining how you can send events to private APIs in a VPC.

- [Should you validate your producer/consumer events?](https://www.boyney.io/blog/2022-08-09-event-validation) - David Boyne asked a portion of the community about event validation, and concluded the result in his Blog post.

- [Bidirectional event integrations with Salesforce and Amazon EventBridge](https://aws.amazon.com/blogs/compute/introducing-bidirectional-event-integrations-with-salesforce-and-amazon-eventbridge/) - Example of using EventBridge to consume and produce events flowing outside your organistion. 

- [Guaranteed event ordering when using Amazon EventBridge as your Enterprise Service Bus](https://leejamesgilmore.medium.com/guaranteed-event-ordering-when-using-amazon-eventbridge-as-your-enterprise-service-bus-ca7a2b62afea) - Lee James Gilmore gives us a detailed example of how to use SNS and SQS FIFO queues with EventBridge and DDB Stream patterns, along with code examples and great diagrams. If you are interested in event ordering then check this blog post out.

- [Enrich your EventBridge events with AWS Lambda](https://www.boyney.io/blog/2022-11-01-eventbridge-enrichment-with-lambda) - Pattern to explore using content enrichment patterns with Amazon EventBridge and using AWS Lambda as the enricher. Using custom rules and metadata to enrich data and put the events back onto the bus for downstream consumers.

- [How to publish large events with Amazon EventBridge using the claim check pattern](https://www.boyney.io/blog/2022-11-01-eventbridge-claim-check) - Need to handle large events with EventBridge but hitting the payload limit? Try using the claim check pattern, here is an example of what the claim check pattern is and example code to do it.

- [Enriching operational events with AWS Serverless, EC2 and EventBridge!](https://aws.amazon.com/blogs/compute/enriching-operational-events-with-aws-serverless/) -  Ben Moses gives us a great blog post to listen to EC2 changes, enrich events using Step Functions and email downstream consumers using SNS. Some great patterns here, recommened diving in if you want to learn more about enrichment and listening to aws events!

- [Introducing EventBridge Scheduler](https://docs.aws.amazon.com/scheduler/latest/UserGuide/what-is-scheduler.html) - If you are using EventBridge custom rules to build schedules, or want to setup millions of schedules for your projects, then check it out!

- [9 Surprises using AWS EventBridge Scheduler](https://dev.to/kumo/9-surprises-using-aws-eventbridge-scheduler-13b6) - [Frédéric Barthelet](https://github.com/fredericbarthelet) deep dives into the Scheduler service, detailling the functionalities it offers, sharing insights on how to maximize its capabilities and steer away from bad design intents.

- [Improved EventBridge Latency Opens Up New Use Cases at PostNL](https://medium.com/postnl-engineering/improved-eventbridge-latency-opens-up-new-use-cases-at-postnl-910fdf6b5dde) - Great read by Luc van Donkersgoed as he explains how PostNL are processing millions of events, and how latency improvements (rolled out in 2023) helped their architecture and is paving the way for new improved usecases. Another reason to love serverless!

- [EventBridge Visuals](https://serverlessland.com/serverless/visuals/eventbridge) - Learn through visuals, David Boyne has been working on visuals to help you learn EventBridge, if you are visual learner these may help you.

- [EventBridge Visuals - Download the Book](https://serverlessland.com/serverless/visuals/eventbridge/download) - Download all the EventBridge visuals offline.

- [Testing Event-Driven Applications Using EventBridge — A Four-Year Journey](https://medium.com/@smorland/testing-event-driven-applications-using-eventbridge-a-four-year-journey-8ed0c80fc4ca) - A great article by Steve Morland on how they are using EventBridge and testing patterns they explored to help. 

## Audio
- [Amazon EventBridge Pipes with Nik Pinkski](https://open.spotify.com/episode/5XiDRadCQRTsFuId9Zavl6?si=iy2RvlTcTN6w1mVx2jcacQ&nd=1) - Folks at AWS give us a 26 minute podcast where Nik Pinkski (Principle Engineer on EventBridge team) helps us understand what is EventBridge Pipes and it's back story.

## Courses

- [Building Event-Driven Applications with Amazon EventBridge](https://explore.skillbuilder.aws/learn/course/external/view/elearning/15008/building-event-driven-applications-with-amazon-eventbridge) - Free training provided by AWS, if you are new to EventBridge or want to learn more this is worth taking

## Patterns

- [Enrich EventBridge events using Lambda and custom rules](https://serverlessland.com/patterns/eventbridge-enrichment-with-lambda) - Enrichment pattern that uses metadata on a given event, and enrichs the data before reaching downstream services.
- [Claim check pattern with S3 and EventBridge Notifications](https://serverlessland.com/patterns/s3-to-eventbridge-claim-check-pattern) - Claim check pattern to handle large data in EventBridge. In this example user uploads a file and S3 events are used to raise domain information. Presigned URLS are used to get the information to downstream consumers.
- [Outbox pattern with EventBridge and DynamoDB](https://serverlessland.com/patterns/dynamodb-streams-to-eventbridge-outbox-pattern) - Using DynamoDB streams to process EventBridge events. First store the data (in this example user information) then raise EventBridge events off the back of it

## Tools

- [EventBridge Lens (VSCode Extension)](https://github.com/boyney123/eventbridge-lens) - Plugin written by David Boyne to help you explore your EventBridge Bus, rules and visualizes them directly in VSCode.

- [evb-cli](https://github.com/mhlabs/evb-cli) - Pattern generator and debugging tool for Amazon EventBridge. Browser targets of events, generate diagrams, generate code bindings and much more. All from the CLI.

- [EventCatalog](https://www.eventcatalog.dev/) - Document your Event Architectures using Markdown files. Use the [Amazon EventBridge](https://www.eventcatalog.dev/docs/development/plugins/eventbridge/intro) plugin to generate docs from your Schema Registry and map them into domains and services.

- [cdk-eventbridge-socket](https://github.com/boyney123/cdk-eventbridge-socket) - CDK construct that creates a WebSocket endpoint for you for any EventBridge rule you are interested in. (Built for debugging + testing )

- [sls-dev-tools](https://github.com/Theodo-UK/sls-dev-tools#eventbridge) - Dev Tools for the Serverless World. Another great CLI tool for serverless support and EventBridge!

- [EventBridge Atlas](https://github.com/boyney123/eventbridge-atlas) - Document, Discover and Share Amazon EventBridge Schemas. Transforms your schemas into documentation.

- [EventBridge Canon](https://github.com/boyney123/eventbridge-canon) - Simple UI to Publish, Save and Share AWS EventBridge Events. Think Postman but for EventBridge.

- [EventBridge Schema Watcher](https://github.com/boyney123/cdk-schema-watcher) - Simple CDK construct with plugin support that allows you to listen for schema changes on eventbridge. For example, send messages directly into Slack when schemas change, perfect for downstream consumers!

- [sls-test-tools](https://github.com/Theodo-UK/sls-test-tools) - Custom Jest Assertions for Serverless integration testing. Test your EventBridge integration with these awesome jest tools. Check if events are raised and the payloads of them.

- [EventBridge Transformer](https://eventbridge-transformer.vercel.app) - An online tool that allows you to quickly generate input paths and input templates for EventBridge. Use your event as a starting point then interactive editors to generate your code. Also see example outputs and validate your input templates/paths.

- [serverless-offline-eventbridge](https://github.com/rubenkaiser/serverless-offline-eventBridge) -  serverless offline plugin that enables eventBridge events 

- [Typebridge](https://github.com/fredericbarthelet/typebridge) - TypeScript toolbox for EventBridge. 

- [EventBridge Ruler](https://github.com/aws/event-ruler) - A Java library that allows you to build applications that can match any number of rules against events at several hundred thousand events per second. 

- [Quamina](https://github.com/timbray/quamina) - Go pattern match library following EventBridge pattern style. Use this package in your applications to only send events to EventBridge if they match the registered patterns. Improves latency and reduces cost in applications.

- [EventBridge Kafka Connector](https://github.com/awslabs/eventbridge-kafka-connector) - An Open Source Kafka sink connector for Amazon EventBridge to send events (records) from Kafka topic(s) to the specified EventBridge event bus. If you are using Kafka and want to integrate with EventBridge, this project may help!

## Example Projects

- [Event Driven Architecture with .NET API's](https://github.com/jeastham1993/event-driven-dotnet-api) - James Eastham has built a great EDA example using NET 6 APIS. This sample project demonstrates how to build an event driven architecture on AWS using ECS Fargate, .NET 6 REST API's, AWS CoPilot and Amazon EventBridge.

- [Serverlesspresso](https://github.com/aws-samples/serverless-coffee) - Open source project for the [Serverlesspresso](https://serverlessland.com/reinvent2021/serverlesspresso) the [Serverless DA Team at AWS](https://serverlessland.com/about) has built using Step Functions, EventBridge and API Gateway.

- [Event Driven Serverless CDK](https://github.com/jeastham1993/event-driven-serverless-cdk). James Eastham gives us another example of an event driven application. This project contains an example of building an AWS native, event driven, customer review analysis application. It uses serverless components and native AWS service integrations. The application is deployed using the AWS CDK, written in C#.
