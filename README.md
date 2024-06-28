# ChatIn

ChatIn is a full-featured chat application designed for seamless communication with channels, direct and group chats, reactions, built-in GIF support, and more.

## Features

- Channels for organized discussions
- Direct and group chats for private and team communication
- Emoji reactions to messages
- Built-in GIF support for expressive conversations
- Edit and delete messages for managing communication flow
- Specialized commands for enhanced functionality

## Technologies Used

- Frontend: React
- Backend: Express, Node.js
- Chat API: Stream Chat API
- SMS API: Twilio

## Installation

1.for client side 
 
     cd client
     npm install
     npm start

2.for serveur side 

     cd serveur
     npm install

3.Set up environment variables:
Create a '.env' file in the serveur directory with the following:

    STREAM_APP_ID=your_stream_app_id
    STREAM_API_KEY=your_stream_api_key
    STREAM_API_SECRET=your_stream_api_secret

    TWILIO_ACCOUNT_SID=your_twilio_account_sid
    TWILIO_AUTH_TOKEN=your_twilio_auth_token
    TWILIO_MESSAGING_SERVICE_SID=your_twilio_messaging_service_sid

4.Start the development server:

    npm run dev
