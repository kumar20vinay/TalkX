# Realtime Chat App with MERN stack

### Introduction
This repo consists of a Realtime Chat Application built with the MERN stack. I built it when I was trying to learn React and the stack for the first time.


### Feature
1. **JWT Authentication**:
- JSON Web Tokens (JWTs) are a secure way to transmit information between parties. They consist of three parts: header, payload, and signature. JWTs can be used for authorization and securely exchanging data1. When a user logs in, the server generates a JWT token containing necessary information for authentication and authorization. This token is sent to the client and stored on the client-side, such as in local storage2.

2. **Private Chat**:
Users can engage in one-on-one private conversations. This feature ensures privacy and allows direct communication between users.

3. **Room Chat**:
Users can create rooms and broadcast messages to specific groups. It’s useful for group discussions or announcements.

4. **Real-time Updates**:
The system provides real-time notifications for various events, such as new messages, user online/offline status, read/unread status, and user join/leave room notifications.

5. **Responsive Web Design**:
The application adapts to different screen sizes and devices, ensuring a consistent user experience.
It supports both light and dark themes for user preference.de

### Technologies
- Database - MongoDB
- Backend - Express.js & Node.js
- Frontend - React.js (with styled-components)
- Real-time messages - Socket.io

### How to use
1. Clone the repo
    ```
    git clone 
    ```
2. go in folder
    ```
    cd TalkX

    ```
3. Divide the console in two parts

4. Enter the server Directory
    ```
    cd server
    npm i
    ```

4. create .env file
   - Create Variables
   ```
    MONGO_URI = YOUR MONGODB URI
    CLIENT_URL = WHERE YOUR CLIENT RUNS
    ACCESS_TOKEN_SECRET = RANDOM STRING
    REFRESH_TOKEN_SECRET = RANDOM STRING
    COOKIE_SIGNATURE = RANDOM STRING
   ```
5. Run the server   
    ```
    npm start
    ```
    If you see "App is listening to port `YOUR_PORT` DB connection Success", you can run the client side.
    
6. go to client Directory
    ```
    cd client 
    npm i
    ```
7. create .env file
    - create variables 
    ```
    VITE_AVATAR_KEY = AVATAR API KEY
    VITE_SERVER_URL = SERVER PORT URL
    ```
8. run the client
    ```
    npm run dev
    ```
Thank You!
