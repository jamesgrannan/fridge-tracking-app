# Fridge-It: A Fridge Tracking App

For our final group project at Northcoders we created an app that can track the contents of your fridge and give you notifications when food is going out of date. There are three ways to input food:
- Manually.
- By taking a picture of it and image recognition will determine what it is.
- By scanning a barcode on the food item.

### A link to our presentation will be posted here when it has been released.

## Setup
It might be quite complicated at the moment to view this app as it is currently not hosted. You would require a firestore database from [Firebase](https://firebase.google.com/) and a clarifai api key to their [food identifcation AI model](https://www.clarifai.com/models/ai-food-recognition) as well as the [Expo app](https://expo.dev/) installed on your phone.
- Clone the repository with this link: https://github.com/jamesgrannan/fridge-tracking-app.git
- Make sure you change directory into this repository.
- Running this in your terminal should install all the necessary packages:

```json
  npm install
```

- You wil need to create an .env file whith your own api keys. The contents being:

```json
  CLARIFAI_API_KEY={insert your Clarifai API key here}
  FIREBASE_API_KEY={insert your Firebase API key here}
```

- To view the app, you will need to run:

```json
  npm run start
```

This will show you a QR code. Open the Expo app and scan the QR code. The app should eventually load, but with an empty fridge. Get adding!

