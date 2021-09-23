# Secure your single page web app with low code on IBM Cloud

## Pre-requisite:

Node package manager installed in your PC using link: https://nodejs.org/en/

To learn how to install node.js in your PC watch this video: https://www.youtube.com/watch?v=__7eOCxJyow

## Step 1: Sign-up/Login to IBM Cloud

If you are an existing user please this link to Login: https://ibm.biz/appsecurity 

And if you are not, don't worry! We have got you covered! There are 3 steps to create your account on [IBM Cloud](<https://ibm.biz/appsecurity>): <br>
1- Put your email and password. <br>
2- You get a verification link with the registered email to verify your account. <br>
3- Fill the personal information fields. <br>
** Please make sure you select the country you are in when asked at any step of the registration process.
  
<img width="688" alt="Screen Shot 2021-05-31 at 11 25 01 AM" src="https://user-images.githubusercontent.com/15332386/120156441-0769d980-c203-11eb-8cb3-29f4a8d5616a.png">


## Step 2: Create an instance of AppID service 

In the search bar type "App ID", click the instance from search result, it will take you to a new window. Click create botton to start your App ID instance 

<img width="545" alt="1" src="https://user-images.githubusercontent.com/16270682/134592823-3f5f8eda-253c-422a-b27c-04b72ebc5704.PNG">


<img width="699" alt="2" src="https://user-images.githubusercontent.com/16270682/134592832-08d6f08f-b1ad-43dd-9d5f-438e24cbf924.PNG">


## Step 3: Download Node.js Sample single page Web Application

From overview, click on Download sample and select Node.js

<img width="639" alt="3" src="https://user-images.githubusercontent.com/16270682/134594513-81d8e849-a270-4d0b-ba17-a96745f0f754.PNG">


Save the zip file named "SampleApp-Node" and extract it on your desktop or any other path that you prefer


## Step 4: Run the Sample application locally 

To confirm your local Host URI was added to the list of allowed redirect URIs.  a Manage Authentication > Authentication Settings, http://localhost:3000/

<img width="654" alt="4" src="https://user-images.githubusercontent.com/16270682/134594819-ac4ae6e7-7cc7-4b71-b171-f7455ba93a1f.PNG">

Open terminal/ cmd/ windows PowerShell and navigate to the sample folder. Run the following commands to build and start the application 

#### Build:

    npm install
    
#### Run app:

    npm start

## Step 5: Test User Authentication

## Step 6: Customize Login Page

## Workshop Resources

- Login/Sign Up for IBM Cloud: https://ibm.biz/appsecurity

- Workshop Replay: https://www.crowdcast.io/e/journey-to-low-code-no-code-app-security-1 

## Done with the workshop? Here are some things you can try further 

 configure social identity providers to set up a single sign-on experience for your app : https://cloud.ibm.com/docs/appid?topic=appid-social&interface=ui
 
