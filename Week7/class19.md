## AWS SQS vs SNS:

> * Q1: What is the difference betweeen SQS and SNS?
>>SQS is for storing messages in a queue with a "pull" model, while SNS is for sending messages to multiple subscribers with a "push" model.

> * Q2: What are some use cases for both SNS and SQS?
>> SNS is used for push notifications and broadcasting messages, while SQS is used for decoupling components and managing message processing.

## AWS SNS and SQS:

> * Q1: Describe how to use SQS and SNS in a “fanout” pattern.
>>In a "fanout" pattern, SNS sends messages to multiple SQS queues, broadcasting to all subscribers.

> * Q2: Explain how “push notifications” work, using SNS.
>> SNS push notifications work by sending messages directly to subscribed endpoints like mobile devices.

## SQS and SNS Basics:

> * Q1: How might a large scale, distributed application make use of a Queue system like SQS?
>> Large-scale distributed applications use SQS to communicate between components, ensuring fault tolerance and independent operation.

## Bookmark and Review:

> * SNS Javascript SDK
>> SNS JavaScript SDK simplifies integrating push notifications and message broadcasting in JavaScript apps.

> * SQS Javascript SDK
>> SQS JavaScript SDK simplifies building scalable and distributed systems with reliable message queuing and processing in JavaScript apps.