## Full-Stack Realtime Chat App

[Live Demo](https://fullstack-realtime-chatapp-g43n.onrender.com)


A real-time chat application built with MERN stack (MongoDB, Express, React, Node.js) and Socket.IO. This app allows users to connect, chat, and share images in real time with an intuitive and modern UI.

## Features

User Authentication: Sign up, log in, and log out securely.

Profile Management: Update profile picture and personal information.

Real-Time Messaging: Send and receive messages instantly using Socket.IO.

Image Sharing: Send text and image messages in real-time.

Online Status: See which contacts are currently online.

Contact Filtering: Search and filter contacts easily.

Theme Customization: Switch between light and dark modes using settings.

Responsive Design: Works seamlessly on desktop and mobile devices.

## Tech Stack

Frontend: React, Vite, TailwindCSS, Zustand (state management), Socket.IO Client

Backend: Node.js, Express, Socket.IO, MongoDB

Other Tools: Cloudinary (for image uploads), Axios (for API requests)

## Installation

Clone the repository:

git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>


Install dependencies for frontend and backend:

npm install --prefix backend
npm install --prefix frontend


Set up environment variables:

Create a .env file in the backend folder:
PORT=5001
MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your JWT Secret Key>
CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
CLOUDINARY_API_KEY=<Your Cloudinary API Key>
CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
Run the development servers:

bash
Copy code
# Backend
npm start --prefix backend

# Frontend
npm run dev --prefix frontend

## Usage
Sign Up / Login: Create an account or log in to start chatting.

Profile Settings: Update profile picture and personal info.

Chat: Click on a contact to start a conversation, send text or images.

Theme: Change the theme from light to dark using the settings.

Online Contacts: Filter and see who is currently online.

