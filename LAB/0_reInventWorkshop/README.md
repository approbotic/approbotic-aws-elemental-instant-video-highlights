# re:Invent 2017 Lab

For this lab, we have pre-configured AWS Elemental Cloud's Live and Delta services for each "team". A team can be 1-3 people who will use a single AWS Account that will use a single AWS Elemental Delta Channel. Each Channel consists of a Live stream unique to that team as well as a Delta Channel. If you try to use a team configuration for multiple people's attempt at this lab, you are going to have a bad time.

Please refer to the [Team Cheat sheet](teams.md) that will be used when assigning Environment Variables in your AWS Lambda Functions within this Lab.

If you are well versed with Serverless Websites infrastructures, you may find yourself ahead of the rest of the class. I would invite you to browse the Python code for each AWS Lambda Function in this repo if you have the extra time.

## Beyond re:Invent 2017 Lab

An AWS Elemental Cloud account will be required with a Deployment that consists of a AWS Elemental Live 2.11 and AWS Elemental Delta 2.1.2 Services. Though you could use the Appliance versions, the use of AWS Lambda requires these Appliances would be Public Internet facing. Please refer to Module 0: [AWS Elemental Configuration](../0_AWSElementalLiveDelta/README.md ) for more details.

## Prerequisites

Basic knowledge of AWS services and a little bit of Python scripting. The understanding of why cats are adorable.

### AWS Account

In order to complete this workshop you'll need an AWS Account with access to create AWS IAM, S3, DynamoDB, Lambda and Amazon Rekognition resources. The code and instructions in this workshop assume only one student is using a given AWS account at a time. If you try sharing an account with another student, you'll run into naming conflicts for certain resources. You can work around these by appending a unique suffix to the resources that fail to create due to conflicts, but the instructions do not provide details on the changes required to make this work.

All of the resources you will launch as part of this workshop are eligible for the AWS free tier if your account is less than 12 months old. See the [AWS Free Tier page](https://aws.amazon.com/free/) for more details.

### Browser

We recommend you use the latest version of Chrome to complete this workshop. You may use the latest version of Firefox and Safari, but the video.js player may not operate correctly and you won't be able to play video.

## Modules

This workshop is broken up into multiple modules. You must complete each module before proceeding to the next.

### re:Invent Workshop

Onward to Module 1: [S3 Static Web hosting](../1_StaticWebHosting/README.md)

## After the Workshop

### Time to cleaup this mess

Now that you have completed the whole lab, it is time to clean up all the things we created in these modules. Please use the checklist here in Module Z: [Clean Up](../Z_CleanUp/README.md)