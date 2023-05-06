# Flash Chat ⚡️


## Goal

The objective of this repository is to learn how to incorporate Firebase into our Flutter apps. I have used Firebase Cloud Firestore as well as the Firebase authentication package to equip my app with a cloud-based NoSQL database and secure authentication methods. 


## What is the project

I build a modern messaging app where users can sign up and log in to chat.


![Finished App](https://github.com/iArpitVerma/Flash_Chat/blob/main/flashchat.gif)


## What I have learnt

- How to incorporate Firebase into your Flutter projects.
- How to use Firebase authentication to register and sign in users.
- How to create beautiful animations using the Flutter Hero widget.
- How to create custom aniamtions using Flutter's animation controller. 
- Learnt all about mixins and how they differ from superclasses.
- Learnt about Streams and how they work.
- Learnt how to use ListViews to build scrolling views.
- How to use Firebase Cloud Firestore to store and retrieve data on the fly.


## How to setup the project

- Clone the repository.
- Open it in VSCode or Android Studio 
- Go to pubspec.yaml and click on 'Pub get' to download all the dependencies used in project.
- Make an account on 'https://firebase.google.com' and click on 'Go to console' on top right corner.
- Then click on 'Create a project' button, then add project name and click on Continue.
- Click on Continue in next page.
- Now Select 'Default account for Firebase' in Select an account section and click on Create Project button.
- Now click on Android button icon (if you are creating for android users).
- You will see 'Add an Android app' page, now fill Android package name of your choice and click on 'Register app' button.
- Now download and add the config file "google-services.json" in android/app directory in your project and click on Next.
- You don't need to add Firebase SDK in project as I have already added it, so click on Next.
- Now click on Continue to console.
- Now we need to setup Authentication for login and sign up, so click on Authentication.
- Now click on Get started and you will see Sign-in method click on it and select a Sign-in provider (Email/Password), click on enable and then Save.
- Now Authentication part is setup.
- Next is Cloud Firestore part for saving the chat messages.
- Go to project overview from the side panel, you will see Cloud Firestore, click on that.
- Next click on Create database button.
- Select Start in production mode option and click on Next button.
- Select a Cloud Firestone location which is closer to your country and click on Enable.
- Now your Firebase is ready, go on VSCode or Android Studio to 'android/app/build.gradle' file and update your application id on line 49th.
- Now you are ready to go.
- Use and Modify the project as per your choice.