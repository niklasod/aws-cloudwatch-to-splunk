# aws-cloudwatch-to-splunk

## Description
Very simple lambda function and subscription filter meant to ship Cloudtrail events from a cloudwatch log group to a lambda. 
Can easily be modified to ship any cloudwatch logs.

## Subscription filter
The subscription filter pattern checks for Root logins on your AWS account. Add any filter you'd like. 

## Costs
Using this lambda will create cost in your account. Use filters to not send all Cloudtrail events to the lambda and keep cost down. Create a budget to make sure you 
don't spend more than you want. 
