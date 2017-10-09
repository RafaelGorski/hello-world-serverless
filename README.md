# hello-world-serverless
Hello Word using Serverless framework + Code + AWS Lambda + AWS SNS + AWS SQS 
For this example I will be using the following logical structure:
PackageHello
  - functionHello

As this example uses serverless framework the service concept I called Package and the function as fucntion.
The concept of packages is not written so I suggest this approach here.  

## Pre requisites

### AWS 
AWS Credentials
  AWS AIM User
  AWS AIM Group

### Dev-Machine
Make sure you have the following tools to run this project:

Node 6.10.3  <-- version used by AWSnode post
NVM - https://github.com/creationix/nvm
Serverless
NPM
Code
Serverless Framework
Github

#### Serverless Config
  Setup your crendentials https://serverless.com/framework/docs/providers/aws/cli-reference/config-credentials/
    serverless config credentials --provider aws --key 1234 --secret 5678

#### Other serverless references
https://serverless.com/framework/docs/providers/aws/guide/serverless.yml/