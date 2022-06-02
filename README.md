# AWS SAM using Typescript with Lambda

_Infrastructure as code framework used_: AWS SAM
_AWS Services used_: AWS Lambda, AWS DynamoDB

## Summary of the demo

In this demo you will see:

- 2 ways to create a project with Lambda functions that are written in typescript using AWS SAM.

This demo is part of a video posted in FooBar Serverless channel. You can check the video to see the whole demo.

Important: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the AWS Pricing page for details. You are responsible for any AWS costs incurred. No warranty is implied in this example.

## Requirements

- AWS CLI already configured with Administrator permission
- AWS SAM CLI installed - minimum version 1.50.0 (sam --version)
- NodeJS 16.x installed

## Deploy this demo

We will be using AWS SAM and make sure you are running the latest version - at the time of writing, this was 1.50.0 (sam --version).

Deploy the project to the cloud:

```
sam deploy -g # Guided deployments
```

When asked about functions that may not have authorization defined, answer (y)es. The access to those functions will be open to anyone, so keep the app deployed only for the time you need this demo running.

Next times, when you update the code, you can build and deploy with:

```
sam deploy
```

To delete the app:

```
sam delete
```

## Links related to this code

- Video with more details: https://youtu.be/GykEaUKDcrk
