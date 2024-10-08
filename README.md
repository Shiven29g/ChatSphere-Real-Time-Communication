Real-Time Chat Application

This is a real-time chat application built using Socket.IO and Node.js. It allows users to send and receive messages instantly in a user-friendly interface.
Key Features

    Real-time messaging
    User identification
    Responsive design with Tailwind CSS
    Message display in chat bubbles
    Auto-scroll for new messages

Technologies Used

    Frontend: HTML, CSS (Tailwind CSS), JavaScript
    Backend: Node.js, Express.js, Socket.IO

Getting Started

Follow these steps to set up and run the application locally.
Prerequisites

    Node.js installed on your machine.

Setup Instructions

    Create a Project Folder:
    Open your terminal and run the following commands:

    perl

mkdir socket-chat-app
cd socket-chat-app

Initialize Node.js Package:
Run this command to create a package.json file:

csharp

npm init -y

Install Required Packages:
Install Express and Socket.IO by running:

lua

npm install express socket.io

Create HTML and JavaScript Files:
Create two files named index.html and index.js.
You can do this by running:

bash

    touch index.html index.js

    Project Structure:
    Your project folder should now contain the following files:
        index.html
        index.js

Implementation
index.html

In index.html, create a simple form for user input, including fields for the user's name and message. Include the Socket.IO client script and the JavaScript code to handle sending and receiving messages.
index.js

In index.js, set up an Express server to serve the HTML file. Create a Socket.IO instance to handle incoming events from the client and broadcast messages to all connected users.
Running the Application

    Start the Server:
    In your terminal, navigate to your project folder and run:

node index.js

Open the Chat Application:
Open your web browser and go to:

    http://localhost:5000

    Test the Application:
    Open multiple tabs of the same URL to chat with yourself or other users in real-time.

Conclusion

This project demonstrates the power of real-time communication using Socket.IO and Node.js. Enjoy chatting!
linkedin-https://www.linkedin.com/in/shiven-gupta-85979227a/
