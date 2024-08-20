
# Monochat

Monochat is a simple chat application built with React and Firebase. It allows users to sign in with Google, send messages, and view messages in real-time. This project is based on the chat app built by [Fireship](https://github.com/fireship-io)


## Features

- Google Authentication
- Real-time messaging
- Responsive design


## Prerequisites
- Node.js and npm installed
- Firebase project set up


## Installation

- Clone the repository

```bash
  npm install my-project
  cd my-project
```
- Install dependencies

```bash
  npm install
```
- Create a .env file in the root directory and add your Firebase configuration

```bash
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
REACT_APP_FIREBASE_MEASUREMENT_ID=your_measurement_id
```
## Usage/Examples
- Start the development server:

```javascript
   npm start
```

- Open your browser and navigate to http://localhost:3000

## Project Structure
- App.js: Main component that handles authentication and renders the chat room or sign-in button.
- ChatRoom() - Function that displays messages and handles sending new messages.
- ChatMessage() - function that renders individual messages.
- SignIn() - function that handles Google sign-in.
- SignOut() - function that handles sign-out.
## Firebase Configuration

The firebase configuration is stored in the .env file. Make sure to create your own and replace the placeholder values with your actual project configuration.
## Acknowledgements

 - [Fireship Tutorial](https://www.youtube.com/watch?v=zQyrwxMPm88)
 - [React](http://reactjs.org/)
 - [Firebase](http://firebase.google.com/)
 - [react-firebase-hooks](https://github.com/CSFrequency/react-firebase-hooks)


