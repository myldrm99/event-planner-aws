# CS683_project 

## Details
Our web application is an online event planner. The users can create and manage events. After signing in the application, the users see a page and can navigate to two different pages. The first one is for viewing existing events. The second one is for creating a new event.  The required information for creating an event includes event title, number of participants, date, time, address and details. In the event viewing section, users can see all the events. They can join events with available quota in that page and the quota of the event is decreased by one. The owner of the event can see the participants and get notifications when someone joins their event.

We will use several AWS services in our application. Amazon Cognito will be used for user registration and authentication. Amazon Route 53 will be used for DNS management and access to application. Amazon CloudFront will be used for static content. Amazon S3 will be used for storing HTML, CSS and Javascript files. Amazon API Gateway will be used for the communication between frontend and serverless backend, and routing user requests to AWS Lambda. AWS Lambda will be used for responses for user requests such as registration, creating events and joining an event. Amazon DynamoDB will be used for keeping the data. Amazon CloudWatch will be used for monitoring performance metrics. Github will be used for CI/CD.

##
You can visit the website [here]( https://eplannergo.com/).

## Architecture
![aws Architecture](https://github.com/myldrm99/cs683_project/blob/main/images/arch.png)

## AWS Services Used
- **Cognito:** User authentication
- **Route 53:** DNS management
- **CloudFront:** Static content delivery
- **S3:** Frontend storage (HTML, CSS, JavaScript)
- **API Gateway:** Request routing
- **Lambda:** Backend logic
- **DynamoDB:** Data storage
- **CloudWatch:** Monitoring

