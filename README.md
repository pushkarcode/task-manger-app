# Welcome to Ofto Task Manager App
Greetings and welcome to Ofto Task Manager, your indispensable ally in conquering tasks and optimizing productivity! Meticulously crafted to streamline your life, Ofto Task Manager transcends the ordinary task manager – it's your personal productivity powerhouse. In today's dynamic world, maintaining order is paramount to achieving success. With Ofto Task Manager, bid farewell to chaos and embrace a structured approach to your daily pursuits. Whether you're a seasoned professional, a student juggling numerous deadlines, or someone aspiring to lead a more organized lifestyle, our application is tailored to cater to your unique requirements.

## Getting Started
Embark on your journey with Ofto Task Manager by following these steps:

1. Registration:

 - Begin by navigating to the registration page through the "Register" link located in the top-right section of the navbar. If you already have an account, click on the "Login" link and sign in to proceed.

2. Login:

 - After successfully logging in, you'll be redirected to the tasks page, showcasing a comprehensive list of all your added tasks. For newcomers, the page may appear empty, prompting you to initiate the process by adding tasks using the "Add Task" button.

3. Adding Tasks:

 - Click the "Add Task" button, where you'll be prompted to provide essential details such as Task Name, Task Description, Due Date, and Task Priority.

4. Task Operations:

 - Upon adding a task, you gain the ability to perform various operations, including updating and deleting tasks.

5. Profile Management:

 - Explore your profile section, offering options for profile viewing, editing, and deletion. Editing enables you to modify your username and email, while deletion ensures the removal of your Ofto Task Manager account.

6. Installation
To run this application locally, follow these steps:

Clone this repository:

git clone https://github.com/pushkarcode/task-manger-app.git
#Navigate to the project folder:

cd task-management-app
Install dependencies for the frontend and backend:

# Install frontend dependencies
cd client
npm install # or yarn install

# Install backend dependencies
cd server
npm install # or yarn install
Configure the environment variables for the backend:

Create a .env.development file in the server directory containing
  ACCESS_TOKEN_SECRET, REFRESH_TOKEN_SECRET, DATABASE_URL = mongodb://localhost:27017/mern-task-management, and FRONTEND_URL
Create a .env file in the client directory containing
  REACT_APP_BASE_API_URL
Run the backend and frontend applications:

# In the backend directory
npm start # or yarn start

# In the frontend directory
npm start # or yarn start
The application should now be running. Access it in your web browser at http://localhost:3000

Embrace the power of Ofto Task Manager to enhance your organizational prowess and elevate your daily efficiency. We are committed to providing you with a seamless and sophisticated task management experience. Your success is our priority!
