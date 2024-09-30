
[Watch Video](https://www.dropbox.com/s/your-video-link)




[Website Link](https://darshstudynotion1718.vercel.app/)

# Study Notion

StudyNotion is a full-fledged MERN stack edtech platform where instructors can upload courses and lectures, and students can purchase and learn courses. The platform allows students to give feedback, instructors to manage course content, and admins to categorize courses. Users can sign up, log in, change their password, and engage with educational content.


## Description
StudyNotion is designed to provide a seamless learning experience. It features:

Instructors can create and upload courses with lectures in different categories.
Students can purchase and learn courses, give feedback, and manage their accounts.
Admin has the ability to manage course categories and overall platform content.
The platform integrates various technologies and tools to ensure a smooth and efficient workflow.
## Features

User Authentication: Signup, login, and password change functionalities.

Course Creation: Instructors can create and upload courses with multiple lectures.

Category Management: Admins can create new categories for organizing courses.

Feedback: Students can provide feedback on courses.

Secure Payment: Integrated with Razorpay for seamless course purchases.

File Uploads: Instructors can upload course materials (video, PDFs, etc.) via Cloudinary.


## Technologies Used

MongoDB: NoSQL database for storing user, course, and category data.
Express.js: Backend framework for creating REST APIs.

React.js: Frontend library for building a responsive user 
interface.

Node.js: JavaScript runtime environment for backend.
Mongoose: ODM for MongoDB.

Cloudinary: For storing and serving course media files.
Razorpay: For handling payments.

Nodemailer: For sending OTPs and other emails.

Redux: State management for efficient frontend handling.

JWT: For secure user authentication.
## Installation

To get a local copy of the project up and running, follow these steps:

Prerequisites:
Make sure you have Node.js installed on your machine.
```bash

git clone https://github.com/yourusername/studynotion.git
cd studynotion

cd server
npm install
npm install nodemon dotenv cloudinary express mongoose jsonwebtoken razorpay cookie-parser otp-generator nodemailer bcrypt cors express-fileupload concurrently


cd ../client
npm install
npm install @ramonak/react-progress-bar @reduxjs/toolkit axios chart.js concurrently copy-to-clipboard react react-chartjs-2 react-dom react-dropzone react-hook-form react-hot-toast react-icons react-markdown react-otp-input react-rating-stars-component react-redux react-router-dom react-scripts react-super-responsive-table react-toastify react-type-animation redux redux-toolkit swiper video-react web-vitals


Set up environment variables:

Create a .env file in both the /server and /client directories.
Add necessary environment variables, such as MongoDB URI, JWT secret, Razorpay API keys, and Cloudinary API credentials.


Start MongoDB (ensure it's running locally or use MongoDB Atlas).


cd server
npm start

cd client
npm start


To run both frontend and backend concurrently:
npm run dev

```
    
## Usage/Examples

Once the project is running, you can visit the following endpoints:

Frontend: http://localhost:3000
Backend (API): http://localhost:5000
Explore the platform as:

Student: Purchase courses, learn, and give feedback.
Instructor: Create courses, upload lectures, and manage content.
Admin: Manage course categories and oversee platform content.


## Project Structure

/studynotion
│
├── /client             # React frontend
│   ├── /public         # Static assets
│   └── /src            # React components, Redux store, pages, and hooks


│
├── /server             # Express backend
│   ├── /controllers    # Route handlers
│   ├── /models         # MongoDB models
│   ├── /routes         # API routes
│   ├── /utils          # Utility functions and middlewares
│   └── server.js       # Entry point for backend
│
├── /config             # Environment variables setup
└── /tests              # Unit tests for backend and frontend

## Contributing

Contributions are welcome! Please follow these steps:

Fork the project.

git checkout -b feature-name


git push origin feature-name


Open a pull request.





## License

[MIT](https://choosealicense.com/licenses/mit/)


This project is licensed under the MIT License.


## contact

Email: darshkumar0609@gmail.com
Phone: +91 8081792286
Feel free to reach out for any queries or collaboration opportunities!
