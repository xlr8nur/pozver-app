# PozVer

PozVer is a social media platform where users can upload photos, like and delete posts, make comments, and follow/unfollow accounts. The project leverages modern web technologies for a seamless user experience.
To start to share your memories with your friends, click ![this](pozver-app.vercel.app) link

![pozver](https://github.com/xlr8nur/pozver-app/assets/97341887/0e260e48-26f6-4b74-8064-3bf64d82718f)

## Table of Contents

- [Overview](#overview)
- [Technologies](#technologies)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Overview

PozVer is designed to provide users with a platform to share their photos and interact with others through likes, comments, and following features. The application is built using React and Chakra UI for the frontend, and Firebase for the backend.

## Technologies

- **Frontend**: React, Chakra UI
- **Backend**: Firebase

## Features

- **Photo Upload**: Users can upload photos.
- **Likes**: Users can like and unlike photos.
- **Comments**: Users can comment on photos.
- **Delete Photos**: Users can delete their own photos.
- **Follow/Unfollow**: Users can follow and unfollow other users.

## Installation

### Prerequisites

- Node.js and npm installed on your machine
- Firebase project set up

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/xlr8nur/pozver-app.git
   cd pozver-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up Firebase:**

   - Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).
   - Add a web app to your Firebase project and copy the Firebase config object.
   - Create a `.env` file in the root directory of your project and add your Firebase config details:

     ```env
     REACT_APP_FIREBASE_API_KEY=your-api-key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
     REACT_APP_FIREBASE_PROJECT_ID=your-project-id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
     REACT_APP_FIREBASE_APP_ID=your-app-id
     ```

4. **Run the application:**

   ```bash
   npm start
   ```

   The application will run on `http://localhost:5173`.

## Usage

Users can access the project by clicking this link: [PozVer App](https://pozver-app.vercel.app).

1. **Sign Up / Sign In:**

   Users can sign up for a new account or sign in to an existing account.

2. **Upload Photos:**

   Once signed in, users can upload photos from their device.

3. **Interact with Posts:**

   Users can like or unlike photos, add comments, and delete their own photos.

4. **Follow/Unfollow:**

   Users can follow and unfollow other users to see their posts in the feed.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## Contact

For any inquiries or feedback, please contact:

xlr8nur@protonmail.com
