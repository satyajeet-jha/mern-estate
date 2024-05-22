
# A Modern Real Estate Marketplace


Welcome to the Modern Real Estate Marketplace, a full-featured web application built using the MERN stack (MongoDB, Express, React, Node.js). This project aims to provide a seamless and secure platform for users to create, manage, and search for property listings with advanced functionalities.


## Features

- Advanced Authentication:

    - JWT: Secure user authentication and authorization using JSON Web Tokens.
    - Firebase: Leverage Firebase for authentication and real-time database functionalities.
    - Google OAuth: Implement Google OAuth for easy and secure user login.
- Real-world CRUD Operations:

    - Perform create, read, update, and delete operations on property listings.
     - Efficiently manage listings with MongoDB as the database.
- User-friendly Features:

    - Image Uploads: Allow users to upload property images for better listing presentation.
     - Property Listing Management: Users can easily manage their property listings through a user-friendly interface.
- Advanced Search Functionality:

    - Implement robust search features to help users quickly find properties that match their criteria.
    - Filter listings by various parameters such as location, price range, property type, and more.


## Installation

To get started with the project, follow these steps:

## Clone the Repository
```bash
git clone https://github.com/satyajeet-jha/mern-estate.git
cd mern-estate

```

## Install Server Dependencies
```bash
cd server
npm install

```

## Install Client Dependencies
```bash
cd ../client
npm install

```

## Set Up Environment Variables
- Create a .env file in the server directory.
- Add your MongoDB URI, JWT secret, Firebase configuration, and Google OAuth credentials.
Example .env file:
```bash
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
FIREBASE_APP_ID=your_firebase_app_id
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

```

## Run the Server
```bash
cd server
npm start

```

## Run the Client
```bash
cd server
npm start
```

# Demo 
https://github.com/satyajeet-jha/mern-estate/assets/72481692/3e398f6d-3560-44d9-be60-67eb2a99abc2



    
