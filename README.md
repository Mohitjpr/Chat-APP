# Chat-APP
Chat Application with Real-time One-to-One Messaging
his MERN (MongoDB, Express.js, React.js, Node.js) stack chat application is designed to provide real-time one-to-one messaging with a user-friendly UI similar to WhatsApp. Users can create accounts, set profile images, and engage in seamless, real-time conversations with other users. The application uses Socket.io for real-time messaging.

Features
One-to-One Real-time Chat: Enjoy real-time messaging with other users, similar to WhatsApp.

User Authentication: Create an account and log in securely.

Profile Image: Set and display your profile image.

WhatsApp-like UI: The application is designed with a user-friendly interface inspired by WhatsApp.

Installation
To get started with this Chat Application, follow these steps:

Clone the repository:

Install server dependencies :

cd server
npm install
Configure environment variables: Create a .env file in the server directory and set the following environment variables:

 MONGO_URL = <your_mongodb_connection_string>
 CLOUD_NAME = <your_cloudinary_cloud_name>
 API_KEY = <your_cloudinary_api_key>
 API_SECRET = <your_cloudinary_secret>
Install client dependencies :

cd client
npm install
Go to client/src/configs/envVariables.js :

Either set APP_ENV = 'local'
or import the value from .env file created in the folder client
Start the server and client: In both the server directory and client:

  npm start
Open your browser and visit http://localhost:3000 to use the Chat Application.

Technologies Used
MongoDB: A NoSQL database for storing user data and chat messages.
Express.js: A Node.js web application framework for building the server.
React.js: A JavaScript library for building the user interface.
Node.js: A JavaScript runtime for building server-side applications.
Socket.io: A library for real-time, bidirectional communication.
Cloudinary: A cloud-based media management service for image upload and storage.

Live at : (https://chatsapp-jd.netlify.app/)

