# AWS Simple Message Forum

![AmplifyForum](https://github.com/tkang/amplify-forum/blob/main/Amplify_Forum.jpg?raw=true)

## Team Members:
Kartik Kapoor | 2021hs70005
BITS ID     | Name
----------  | -----
2021hs70014 | Navya Khurana
2021hs70013 | Ayush Behl
2021hs70004 | Kartik Kapoor
2021hs70038 | Sudhit Jain

## Overview

We will create a new project using Create Next App.

We will then use Amplify CLI to set up AWS Cloud environment and use Amplify JS Libraries to connect our Next.js app to our back-end on AWS Cloud

This project will be a fully-serverless application with following architecture.

[Application URL](https://dev.d2gyu8pz49zp5v.amplifyapp.com/)

### Demo Video

![Demo](https://github.com/navyakhurana/aws-message-forum/blob/main/P1_CCAssignment_Demo%20Video.mp4)

### Architecture

![Architecture](https://github.com/tkang/amplify-forum/blob/main/amplify-architecture.png?raw=true)

### Steps Overview

- Next.js application
- Web application Hosting
- Authentication
- GraphQL API : query, mutation, subscription, filtered subscription
- Authorization
- Storage with S3
- Deleting the resources

### Features we will implement

1. Application hosting
2. Authentication : Sign Up, Login, Signout
3. Data Modeling

- There can be N Topics
- A Topic can have N Comments.

4. Authorization

- Authenticated (Logged-in) users can create, read, update, delete a
  Topic and Comment. They can only update and delete their own.
- Users in Moderator group can read, update, and delete Topics and
  Comments.
- Authenticated (Logged-in) users can read all Topics and Comments.

5. Application UI

- List Topics
- View Topics with Comments

6. Add and delete records (Topic, Comment)
7. Realtime updates with Subscription

8. Data storage with S3 : Upload files to S3

### Development Environment

Before we start, please install

- Node.js v10.x or later
- npm v5.x or later
- git v2.14.1 or later



