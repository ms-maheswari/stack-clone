# StackOverflow Clone

This project is a clone of the popular Q&A platform StackOverflow. It allows users to ask questions, provide answers, and interact with a community of users.

## Features

- Authentication: Users can sign up for an account, log in, and log out. Authentication is required to ask questions and provide answers.
- **Question & Answer**: Authenticated users can ask questions and provide answers to existing questions.
- **Community**: Users can share images and videos with the community. They can like, comment, and share posts.
- **Chatbot**: The application features a chatbot for user assistance. It includes email validation by sending an OTP to the user's email address via SMTP.
- **Membership Plans**: Users can choose from basic, silver, and premium membership plans, each with its own set of features and benefits.

## Tech Stack

- **Frontend**: React.js, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Email Service**: SMTP for sending verification emails
- **Hosting**: Vercel (for deployment)

## Setup

1. Clone the repository:

   git clone https://github.com/ms-maheswari/stack-clone.git

2. Navigate to the project directory:
 
   cd stackoverflow-clone

3. Install dependencies:
   
   npm install

4. Set up environment variables:

   Create a .env file in the root directory and add the following variables:

   PORT=5000
   MONGODB_URI=your_mongodb_url
   JWT_SECRET=your_jwt_secret
   EMAIL_SERVICE=your_email_service
   EMAIL_USERNAME=your_email_username
   EMAIL_PASSWORD=your_email_password

   Replace your_jwt_secret, your_email_service, your_email_username, and your_email_password with your own values.

5. Start the server:
   
   npm start

6. To start the frontend development, navigate to the project directory:

   cd client

7. Start the frontend:

   npm start
