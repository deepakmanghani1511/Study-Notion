# StudyNotion Edtech Project

**StudyNotion** is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.
StudyNotion aims to provide:
 - A seamless and interactive learning experience for students, making education more accessible and engaging.
 - A platform for instructors to showcase their expertise and connect with learners across the globe.

 In summary, StudyNotion is a versatile and intuitive ed-tech platform that is designed to provide an immersive learning experience to students and a platform for instructors to showcase their expertise. In the following sections, we will delve into the technical details of the platform, which will provide a comprehensive understanding of the platform's features and functionalities.


<!-- ##LIVE WEBSITE LINK: https://studynotionplatform.vercel.app/ -->

## Features

### For Instructors

- **User Authentication**: Instructors can log in using their credentials.
- **Course Creation**: Instructors can create and manage courses, including course details and pricing.
- **Lecture Upload**: Instructors can upload lectures for their courses.
- **Payment Processing**: Integrated Razorpay payment gateway for collecting payments from students.
- **Enrollment Tracking**: Instructors can see the number of students enrolled in each course.
- **Revenue Tracking**: Instructors can track the revenue generated from each course.
- **Interactive Charts**: Utilizes npm chartjs package to provide interactive data visualization.

### For Students

- **User Authentication**: Students can also log in with their own accounts.
- **Course Enrollment**: Students can purchase courses and enroll themselves.
- **Review System**: Students can leave reviews for courses using the React-Stars package.
- **Review Display**: Reviews are displayed in a slider format using the Swipe Slider package.
- **Interactive UI**: Offers a user-friendly and interactive user interface.
- **Media Posting**: Utilizes Cloudinary for media file storage.
- **Database**: MongoDB is used as the database for storing data.

## Technologies Used

- Frontend: React, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Payment Gateway: Razorpay
- Media Storage: Cloudinary
- Data Visualization: Chart.js
- UI Components: React-Stars, Swipe Slider, and more.

## Getting Started

### Prerequisites
- JavaScript
- React or Redux
- Node.js
- npm or Yarn
- MongoDB

### Installation
1. **Clone the repository:**
2. 
3. **Install dependencies for the server:**
    ```cd server
    npm install
4. **Install dependencies for the client:**
    ```cd client
    npm install
5. **Set up environment variables:**
    In the server directory, create a .env file and configure your environment variables (e.g., database URI, port number, Razorpay key, etc.).
    
6. **Start the server:**
    ```cd server
    npm run dev
7. **Start the client:**
    ```cd ../client
    npm run dev
## Contributing
I welcome any and all contributions! Here are some ways you can get started:

- Report bugs: If you encounter any bugs, please let us know. Open up an issue and let us know the problem.
- Contribute code: If you are a developer and want to contribute, follow the instructions below to get started!
- Suggestions: If you don't want to code but have some awesome ideas, open up an issue explaining some updates or imporvements you would like to see!
- Documentation: If you see the need for some additional documentation, feel free to add some!

## Instructions

- Fork this repository
- Clone the forked repository
- Add your contributions (code or documentation)
- Commit and push
- Wait for pull request to be merged
