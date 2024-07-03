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

<img width="345" alt="image" src="https://github.com/mugaboronald1/Assignement3/assets/99381533/f82b77a2-cced-42f7-8b17-c4f768bd04b1">


