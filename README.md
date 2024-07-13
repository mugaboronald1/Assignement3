## Authentication App

## Overview
This app is designed to demonstrate the implementation of several key Android features including Broadcast Receivers, Shared Preferences, and Authentication APIs. The app has the following functionalities:

- Detecting Internet connectivity and showing a toast message on connectivity changes.
- Creating a BroadcastReceiver to notify the user with a toast and ring when the battery reaches a specified threshold while charging.
- Implementing Shared Preferences to toggle between Light and Dark Mode.
- Providing authentication through Email and Password as well as Social Media Authentication.

## Features

### 1. Internet Connectivity Detection
The app detects changes in Internet connectivity and displays a toast message accordingly.
- Implementation involves creating a BroadcastReceiver that listens to connectivity changes and responds with the appropriate message.

### 2. Battery Threshold BroadcastReceiver
The app has a BroadcastReceiver that monitors the battery level.
- When the battery level reaches 90% while charging, the app will toast a message and ring to notify the user.

### 3. Shared Preferences
The app allows the user to toggle between Light Mode and Dark Mode.
- The user's preference is saved using Shared Preferences and persists across app launches.

### 4. Authentication API

#### Email and Password Authentication
- Users can sign up and sign in using their email and password.
- Firebase Authentication is used to handle email and password sign-up and sign-in processes.

#### Social Media Authentication
- The app provides options for users to authenticate via social media platforms like Google and Facebook.
- Firebase Authentication handles the integration and user management for social media logins.

<img width="232" alt="image" src="https://github.com/mugaboronald1/Assignement3/assets/99381533/d9353a7e-ea44-4a0f-8928-bb594b1e365f">
<img width="286" alt="image" src="https://github.com/mugaboronald1/Assignement3/assets/99381533/c02eb371-acb6-47ca-9232-8c4c7c82cf9d">
<img width="182" alt="image" src="https://github.com/mugaboronald1/Assignement3/assets/99381533/9232d247-4d88-40f6-b517-d1e961e3ff28">



<img width="737" alt="image" src="https://github.com/mugaboronald1/Assignement3/assets/99381533/b8864086-e404-487c-94e2-ebeb06ccadb7">
<img width="534" alt="light dark" src="https://github.com/user-attachments/assets/367f7fc7-1182-416b-bf79-dc0949644d85">
<img width="377" alt="image" src="https://github.com/user-attachments/assets/7e0c52b9-36de-422a-b3e1-c0e86ae41196">








