Workout App
About
Workout App is a web application designed to help users track and manage their fitness routines. With a focus on user-friendly design, this app allows users to easily create, modify, and monitor their workouts, providing a comprehensive tool for personal fitness management.

Features
User Authentication: Secure login and registration system to manage user accounts.
Workout Tracking: Users can add and track different types of workouts and exercises.
Progress Monitoring: Includes features to help users monitor their progress over time.
Responsive Design: Ensures a good user experience on both desktop and mobile devices.
Technologies
Frontend: React, Redux for state management, and Sass for styling.
Backend: Node.js with Express for the server, Prisma as the ORM, and PostgreSQL for the database.
Deployment: The application is set up to be containerized using Docker for easy deployment.
Setup
To get this project up and running on your local machine:

Clone the repository:

git clone https://github.com/bokolyar2la/workoutApp.git
Install dependencies:

For the backend:
cd workout-app-back
yarn install
For the frontend:
cd wa-client
yarn install
Set up the environment variables:

Copy the .env.example file to .env and fill in the necessary details such as the database URL and any API keys.
Start the development servers:

For the backend:
yarn dev
For the frontend:
cd wa-client
yarn start
Contribution
Contributions to the project are welcome! You can contribute by improving the code, adding new features, or reporting and fixing bugs.
