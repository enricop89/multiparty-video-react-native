# Multiparty Video

This sample application shows how to build a Video Conference application
using `opentok-react-native` library.

Check out the blog post for a complete guide: 

## Configure

Before running the application, you need to configure it to use the API key
of your OpenTok project, along with an OpenTok session ID and token.
For development purposes, you can obtain a session ID and token by navigating
to your [TokBox account](https://tokbox.com/account/#/) page, selecting a
project, and scrolling to the bottom of the page where it says `Generate Token`.

Copy the config.example.js into a new `config.js` file and add the API key, session ID,
and token you obtained from your TokBox account:

```
// Set Credentials
const API_KEY = '';    // Add your API key.
const SESSION_ID = ''; // Add the session ID.
const TOKEN = '';     // Add the token.
```

## Installation

1. run `npm install` on the project directory
2. 

## Run

### Android

- Run `npm run android`.

***Note: If you're running the app on the simulator, you will see a simulation
for your publisher because the simulator doesn't have a camera.***

### iOS

- Run `npm run ios`.

***Note: If you're running the app on the simulator, you will see a simulation
for your publisher because the simulator doesn't have a camera.***