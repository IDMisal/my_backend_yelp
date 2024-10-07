# Welcome to My Backend Yelp
***
## Demo
You can check out the demo of this Dropbox clone [here](https://d1f6vczca6lyhn.cloudfront.net).

## Task
The task is to deploy Yelp application built with ReactJS to the cloud using AWS services like Amplify and Lambda. The challenge is to make sure the application is hosted properly with authentication and GraphQL integration. The goal is to get it fully functional in a production environment while utilizing AWS's free tier for hosting.

## Description
This project required deploying a pre-built ReactJS application (similar to Yelp) into AWS Amplify, incorporating user authentication, and setting up a GraphQL API. The original code needed adjustments, particularly around authentication and GraphQL queries/mutations, to ensure it integrates smoothly with Amplify’s services.

I worked through configuring AWS Amplify, deploying the app, and making sure that all required resources such as the authentication service (Cognito) and API (GraphQL) are correctly set up. AWS Amplify also provides hosting and S3 storage, which is used for the web application deployment.

## Installation

1. Clone the repository:
 `git clone https://github.com/username/my-yelp.git`
2. Install all dependencies:
 `cd my_yelp`
 `npm install`
3. Set up AWS Amplify by initializing the project:
 `amplify init`
4. Add hosting and authentication:
 `amplify add auth`
 `amplify add hosting`
5. Deploy to AWS:
 `amplify push`

## Usage
Once the project is set up and deployed, users can create accounts, sign in, and interact with the Yelp-like app by adding and viewing restaurant reviews. The authentication feature ensures that only authorized users can add new reviews, making it a secure system.

 * To run the app locally:
  `npm start`

 * For production, the app is hosted [here](https://d1f6vczca6lyhn.cloudfront.net).
 
 # Issues Encountered
    During deployment, I encountered some errors related to AWS CloudFormation stacks and resource creation, especially when configuring hosting (S3 and CloudFront). These errors were resolved by carefully reviewing the bucketName parameter and reconfiguring the hosting service.
    
### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
