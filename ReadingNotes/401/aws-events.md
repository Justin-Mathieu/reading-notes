# AWS Events

## AWS SQS vs SNS

What is the difference betweeen SQS and SNS?

- SNS is a distributed publish service and SQS is a queuing service.  

What are some use cases for both SNS and SQS?

-SNS could be used for batching messages, or processing messages in multiple ways. SQS coulbd be used as a si,ple queue or if only one subscriber is needed.  

## AWS SNS and SQS

Describe how to use SQS and SNS in a “fanout” pattern.

- The topic is being sent to many other services or subscribers.

Explain how “push notifications” work, using SNS.

- The topic is sent to the service that handles the notification and is sent form there.  

## SQS and SNS Basics

How might a large scale, distributed application make use of a Queue system like SQS?

- To ensure things are processed ion the correct order.  
