# Firebase Authentication for Flask Application

## 🛠️ Overview
This project provides a streamlined approach to integrating Firebase Authentication into your Flask applications, offering robust user authentication features. With support for various authentication methods including email/password, social media logins (Google, Facebook, Twitter, etc.), this setup ensures a secure and efficient user authentication process. Key features include user registration, login, password reset, and adherence to best security practices like password hashing and token-based authentication.

## ⚙️ Technologies Used
 - **Backend:** Flask, Firebase
 - **Frontend:** HTML, CSS, Bootstrap


## 🌟 Getting Started
 - ### Install Dependencies
    Run `pip install -r requirements.txt` to install all the requirements.
 - ### Firebase Setup for Project

   - Create a [firebase](https://firebase.google.com/) project, set up a web project and get all the `Project Configurations` from `Project Settings`.

   - Navigate to the **Authentication** section in your firebase project and enable the `Email and Password`
 authentication.

   - The `Project Configurations` will look as follows :-
```bash
  "apiKey": YOUR_API_KEY ,
  "authDomain": YOUR_AUTH_DOMAIN,
  "databaseURL": YOUR_DATABASEURL,
  "projectId": YOUR_PROJECT_ID,
  "storageBucket": YOUR_STORAGE_BUCKET,
  "messagingSenderId": YOUR_MESSAGING_SENDER_ID,
  "appId": YOUR_APP_ID,
  "measurementId": YOUR_MEASUREMENT_ID 
```
- ### Setup Environment for the project
   - Now create a `.env` file in your project dreictory and include the following parameters as it is :-
```bash
export FIREBASE_APIKEY=YOUR_API_KEY
export FIREBASE_AUTHDOMAIN=YOUR_AUTH_DOMAIN
export FIREBASE_DATABASEURL=YOUR_DATABASEURL
export FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
export FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
export FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
export FIREBASE_APP_ID=YOUR_APP_ID
export FIREBASE_MEASUREMENT_ID=YOUR_MEASUREMENT_ID
``` 

- ###  Now Just, Run the project
  - To the run the project, go to the `bash` terminal of VSCode or any other code editor and run `./start_server.sh`.
  - You don't have to care about setting `.env` then yourself then.

## 🤖 References

Github - [MBSA-INFINITY](https://github.com/MBSA-INFINITY)
