# Study Notion

Study Notion is an EdTech (Education Technology) web application developed using the MERN stack.

## Note
This project is intended as a learning tool and can be used as a sample project for educational or personal projects.

## Features
- **User Authentication**: Secure user registration and authentication using JWT (JSON Web Tokens). Users can sign up, log in, and manage their profiles with ease.
- **Courses and Lessons**: Instructors can create and edit courses. Students can enroll in courses, access course materials, and track their progress.
- **Progress Tracking**: Students can track their progress in enrolled courses, view completed lessons, scores on quizzes and assignments, and overall course progress.
- **Payment Integration**: Integrates with Razorpay for payment processing, allowing secure payments for course enrollment and other services.
- **Search Functionality**: Built-in search feature to find courses, lessons, and resources quickly.
- **Instructor Dashboard**: Comprehensive dashboard for instructors to view information about their courses, students, and income, with charts and visualizations for clear data presentation.

## Important
- **Backend** is in the `server` folder.
- Create categories (e.g., web dev, Python, etc.) before uploading courses. Without categories, courses cannot be added.
  - To create categories, create an Admin account and go to the dashboard, then the admin panel.
  - To create an Admin account, sign up with a student or instructor account, then change the `accountType` to 'Admin' in your database under the users model.

## Installation

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/rizwan0713/Study-Notion.git

The project is set up to use postcss-cli to process your CSS files. You can add your own tailwind.config.js file to customize your Tailwind setup.
