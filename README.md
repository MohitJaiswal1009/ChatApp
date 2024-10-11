# MERN Stack ChatApp

This is a real-time chat application built using the MERN (MongoDB, Express, React, Node.js) stack. Users can register, log in, send messages to each other, and see when someone is online through a green indicator icon.

---

## Features

### User Functionality:
1. **User Registration**:  
   Users can register by providing an email and password.

2. **Login**:  
   Users can log in with their credentials.

3. **Real-Time Messaging**:  
   Users can send messages to other registered users in real-time.

4. **Online Status**:  
   Users who are online will be shown with a green dot next to their name, indicating their availability.

---

## Tech Stack

### Frontend:
- **React.js**: Handles the user interface and dynamic components.
- **Socket.io-Client**: Manages real-time communication between users for chat.

### Backend:
- **Node.js & Express.js**: Provides the backend server and RESTful APIs.
- **MongoDB & Mongoose**: Manages user data, chat history, and authentication.
- **Socket.io**: Facilitates real-time, bi-directional communication for messaging.

---

## Features in Detail

### Real-Time Messaging:
- Uses **Socket.io** to enable real-time, bi-directional communication between users. Messages are instantly delivered, and users can chat with each other in real-time.

### Online Status Indicator:
- Users who are online are displayed with a green dot next to their username, letting other users know who is available for a conversation. This is managed using Socket.io events.

### Authentication:
- **JWT (JSON Web Tokens)** is used to handle user authentication, allowing secure login and session management.

