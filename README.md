# Deploy to firebase hosting
In this guide, you will learn how to deploy your tezjs site to Firebase Hosting.

# Pre-requisites
Make sure you have:
  - Firebase account.
  - node installed in your machine.
  - created a firebase project.

# Deployment
Go to https://console.firebase.google.com/ to create a firebase project 
1. Install the firebase-cli:
   `npm install -g firebase-tools`
2. Login into firebase by running this below command:
   `firebase login`
    You can test if the CLI is correctly installed by running `firebase projects:list`, which should show you a list of your Firebase Projects.     
3. Initialize the firebase using command:
   `firebase init`
5. Deploy the dist into firebase using command:
   firebase deploy
   
# References
  - Firebase cli reference: `https://firebase.google.com/docs/cli`
  - Get Started with Firebase Hosting: `https://firebase.google.com/docs/hosting/quickstart`
