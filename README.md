# appsync-quick-start

In this project I have sample code that will allow you to get started quickly with a very simple create and read application behind a managed GraphQL API backend. This is just a sample that should be used for learning purposes, it’s not one size fits all and you’ll need to adapt and change for your specific use cases.

## Quick Start!

### Prerequisites
Node v12 or later should be installed locally.
The Serverless Framework v3 should be installed:
```
npm install serverless@3 -g
```
### Steps
#### 1. Fork and clone the repository
You should work within your own clone/fork of the repository so you can freely commit and push changes.

1. Fork the repository on GitHub
2. Clone the forked repository
#### 2. Install packages
You should run `npm ci` in the root directory to install all package dependencies.

#### 3. Deploy the artifact
After setting your `AWS Credentials` you should run the command `npx sls deploy` in  the root directory