# WorkoutApp

## Description
Fitness planning and tracking single page application that allows users to create, customize, and monitor their fitness goals. The application is split into two main parts: the front-end (client side) and the back-end (server side).

## Features
- **User Authentication and Registration**: Allows users to register and log in to access their workouts.
- **Workout Management**: Users can create, view, edit, and delete scheduled workouts.
- **Progress Tracking**: The app provides features to track the completion of exercises and the user's progress.
- **User Interface**: A clean and intuitive interface that makes navigation and usage of the application straightforward.

## Technologies
- **Front-end**: React, Redux for state management, and Sass for styling.
- **Back-end**: Node.js with Express for the server, Prisma as the ORM, and PostgreSQL for the database.
- **Deployment**: The application is set up to be containerized using Docker for easy deployment.

## Local Setup
To run the application locally, follow the instructions below:

### Dependencies
For the backend:
cd workout-app-back
yarn install

For the frontend:
cd wa-client
yarn install

###
Start the development servers:

For the backend:
yarn dev
For the frontend:
cd wa-client
yarn start

### Clone the Repository
bash
git clone https://github.com/bokolyar2la/workoutApp.git
cd workoutApp
