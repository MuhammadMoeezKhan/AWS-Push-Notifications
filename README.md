# AWS-Push-Notifications

#### Want to push notifications to your teams, or alert your customers/clients of an important update? Then this is the app framework you need!

#### I created an Andoird application framework backed by Google Firebase and AWS Services to push notifications to user endpoints!

<br>

The project utilizes: 
- Google Firebase  project services 
- Amazon AWS SNS Topics, SQS Queues, and Lambda Functions that use SNS points to invoke the Firebase Android services which are connected with the Android Studio Project. 
- Android Loaders, Fragments, Lifecycle methods, User Permissions, and also implements the Firebase Messaging Service

<br>

### Gif#1: Visual Representation: Extracting & Collecting the User's Device Token
##### As the users register their account and launch the application, the life cycles method's of a certain activity are called. These methods generate a unique code for each device that is that copied to the developer's clpiboard (just for demo, else sent directly to Firebase)
<p align="center">
  <img src="http://g.recordit.co/PAPG7PCUoY.gif" alt="animated" />
</p>

<br>


### Gif#2: Testing A Push Notification By Running A Lambda Function!
##### Running an AWS Lambda function that used the SNS topics and endpoints to invoke Firebase services and Android Toasts in-app
<p align="center">
  <img src="http://g.recordit.co/EraRC3Q2iM.gif" alt="animated" />
</p>

<br>


### Gif#3: Running A Test On The Lambda Function That Invokes Google Firebase Servics To Push A Notification To Use Endpoints!
##### Node.js Lambda function test is successfull --> pushes notification onto app using Firebase
<p align="center">
  <img src="http://g.recordit.co/hc2zJfPwCf.gif" alt="animated" />
</p>

<br>
