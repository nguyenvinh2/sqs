#SQS

## Introduction

This application allows users to send and receive messages from their queue programmatically

## Reference

https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/java/example_code/sqs/src/main/java/aws/example/sqs

Instructions

In the AWS console, create a Queue and remember the Queue name

To run this app:
    
    Ensure you have installed AWS Toolkit
    Ensure you have set your AWS profile with SQS Authorization
    Use IDE or gradle to run application (gradle CLI: gradle run)
    Application will prompt for user inputs:
        send or receive messages to Queue
        The Queue Name in your SQS to send a message to (found in your AWS console)
        The message itself depending on whether the send or receive message is inputted



        
    
    