**Imagify – AI Text-to-Image Generation Platform**

**Project Overview**

Imagify is a full-stack web application that converts text prompts into AI-generated images using the ClipDrop API.

The platform allows users to generate creative images from simple text descriptions, manage their generated images, and access premium features through a secure payment system. This project demonstrates the integration of modern frontend technologies, backend APIs, AI services, and secure payment gateways to deliver a seamless user experience.

**Key Features**

🔹 **AI Image Generation**
Generate high-quality images from text prompts using the ClipDrop AI API.

🔹 **User Authentication**
Secure login and registration system for managing user accounts.

🔹 **Image History Management**
Users can view and manage previously generated images.

🔹 **Secure Payment Integration**
Integrated Razorpay payment gateway for accessing premium features.

🔹 **Modern Responsive UI**
Designed a clean and responsive user interface using ReactJS and Tailwind CSS.

🔹 **Smooth Animations**
Enhanced user interaction using Framer Motion animations.

🔹 **Real-Time Notifications**
Implemented React-Toastify for user-friendly notifications.

**Tech Stack**
**Frontend Technologies**

🔹ReactJS

🔹Tailwind CSS

🔹Framer Motion

🔹React Router DOM

🔹React Toastify

🔹Context API

**Backend Technologies**

🔹Node.js

🔹Express.js

🔹Database

🔹MongoDB

**API Integrations**

🔹ClipDrop API – AI Image Generation

🔹Razorpay – Payment Processing

**Application Workflow**

🔹 User enters a text prompt in the application.

🔹 The React frontend sends a request to the Node.js backend.

🔹 The backend communicates with the ClipDrop API to generate the image.

🔹 The generated image is returned to the frontend.

🔹 Image data and user information are stored in MongoDB.

🔹 Users can view their generated images and history.

**Project Structure**

Imagify
│
├── client
│   ├── public
│   └── src
│       ├── assets
│       ├── components
│       ├── context
│       └── pages
│
├── server
│   ├── controllers
│   ├── routes
│   ├── models
│   ├── middleware
│   └── config
│
└── README.md

**Installation and Setup**

**1.Clone the repository**
git clone https://github.com/yourusername/imagify.git

**2.Navigate to the project folder**
cd imagify

**3.Install backend dependencies**
cd server
npm install

**4.Install frontend dependencies**
cd client
npm install

**5.Environment Variables**
Create a .env file inside the server folder and add:

MONGO_URI=your_mongodb_connection
CLIPDROP_API_KEY=your_clipdrop_api_key
RAZORPAY_KEY_ID=your_key
RAZORPAY_SECRET=your_secret
JWT_SECRET=your_secret

**6.Run the Backend Server**
npm run server

**7.Run the Frontend Application**
npm run dev


**Learning Outcomes**
🔹 Built a full-stack AI-powered web application.
🔹 Integrated AI APIs with web applications.
🔹 Implemented secure payment gateway integration.
🔹 Managed application state using React Context API.
🔹 Designed responsive user interfaces using Tailwind CSS.
🔹 Developed RESTful APIs using Node.js and Express.


**Author**
Shafiya Uzama Vadulapalli
Full Stack Developer
