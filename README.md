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

1.**Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/tarun/Study-Notion.git
   ```
2.Install the required packages:

   ```bash
   cd Study-Notion
   npm install 

   cd server<img width="1905" height="932" alt="99eec84<img width="1755" height="933" alt="a4fb6426-b2a5-40f5-b3b1-8679fb4202e9" src="https://github.com/user-attachments/assets/5e0231e1-5d1a-430a-b3ef-32a015b09118" />
d-5328-4581-9e97-ad1622d7615a" src="https://github.com/user-attachments/assets/b87dc93e-46c3-41a5-bf8f-eb3e25dca995" />

   npm install
   ```
3.About us Page:<img width="1887" height="964" alt="38cd78c0-901c-4342-a2f2-dea349e52a80" src="https://github.com/user-attachments/assets/49949344-e503-4bf3-a7da-95d9a2d7cbe1" />

Create a .env file in the root directory and in the /server directory.
as database connection details, JWT secret, and any other necessary configurations. Check th<img width="1868" height="961" alt="fcad765c-44a3-4b5e-b50d-e477f1674e3f" src="https://github.com/user-attachments/assets/89ec6c51-6265-44de-8ed8-b47de690a259" />
e .env.example files for more info.

4.Start the development server.<img width="1895" height="957" alt="HomePage" src="https://github.com/user-attachments/assets/ef709cbb-7c67-4091-aa6d-66807c94a547" />

```bash
npm run dev<img width="1895" height="957" alt="HomePage" src="https://github.com/user-attachments/assets/34cebdd4-758a-4454-8e99-1d095f220d91" />

```
5.Open the project in your browser at http://localhost:3000 to view your project.

The project is set up to use postcss-cli to process your CSS files. You can add your own tailwind.config.js file to customize your Tailwind setup.

