#  Firebase Authentication App
### Easy
This is a basic user authentication app built with **React**, **Firebase**, and **React Router**. It demonstrates a complete user authentication flow using Firebase’s Email/Password method.

---
##  Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Click **"Add project"** → give it a name and finish setup
3. Inside the project, click **"Web" icon** to register your app
4. Copy the provided **Firebase config**
5. Go to the **Authentication** tab → Enable **Email/Password** sign-in

##  Add Environment Variables

In the root of the project, create a `.env` file and paste our Firebase config like this:

VITE_FIREBASE_API_KEY="AIzaSy..."
VITE_FIREBASE_AUTH_DOMAIN="your-project-id.firebaseapp.com"
VITE_FIREBASE_PROJECT_ID="your-project-id"
VITE_FIREBASE_STORAGE_BUCKET="your-project-id.appspot.com"
VITE_FIREBASE_MESSAGING_SENDER_ID="1234567890"
VITE_FIREBASE_APP_ID="1:1234567890:web:..."

##  Features

- Signup with email and password
- ![image](https://github.com/user-attachments/assets/44eeabc5-4e6f-4965-b177-d80119803958)
  ![image](https://github.com/user-attachments/assets/d54e55d3-3ff1-403b-9519-dc4731378b3e)

- Login and logout functionality
- ![image](https://github.com/user-attachments/assets/10d1ca70-5cf9-4508-ba15-c6bbb1d11983)
  
- Protected dashboard route
- ![image](https://github.com/user-attachments/assets/a0c485f1-5cf4-422e-8dbb-61b990a50702)

- Persistent auth state using Firebase
- Simple routing with React Router
  ![image](https://github.com/user-attachments/assets/fe17af87-1ba6-4f17-a256-f200b380b922)


## Auth Flow
Visit /signup → create a user account

Login via /login

Dashboard at /dashboard is protected and accessible only when logged in

Logout returns the user to login screen

