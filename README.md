# Pro-Task-Suite
a professional TODO list suite with all the features and packages for users to manage their activities with notifications and reminders to complete tasks. Users can also add and customize tasks. Can write and pin tasks or quotes etc

ProTask Suite - A Professional TODO List Application

ProTask Suite is a comprehensive, feature-rich TODO list application designed to help you manage your tasks, track your activities, and stay productive. It's built with modern technologies like React, Firebase, and Tailwind CSS, providing a seamless and real-time experience.

Features

📝 Full Task Management: Create, edit, delete, and mark tasks as complete with a simple and intuitive interface.

🎨 Task Customization: Add due dates, set priorities (Low, Medium, High), and include detailed notes for each task.

📌 Pinning: Pin important tasks, motivational quotes, or notes to a dedicated "Pinned" section for quick access.

🔔 Notifications & Reminders: Get browser-based notifications for tasks that are due soon. (Requires browser permission).

📊 Activity Tracker: A dedicated view to see your completed tasks and track your productivity over time.

☁️ Real-time Sync: Powered by Firebase Firestore, your tasks are synced in real-time across all your devices.

🔒 User-Specific Data: All your data is stored securely and is private to you.

📱 Responsive Design: A clean, modern, and fully responsive UI built with Tailwind CSS, ensuring a great experience on any device.

Getting Started

Prerequisites

Node.js and npm (or yarn) installed on your machine.

A Firebase project.

Setup Instructions

Clone the repository or download the source code.

Install Dependencies:
Open your terminal in the project directory and run:

npm install


This will install all the packages listed in the package.json file.

Set up Firebase:

Go to the Firebase Console and create a new project.

In your project, go to Project settings > General.

Under "Your apps", click on the web icon (</>) to add a new web app.

Copy the firebaseConfig object.

Important: This application is designed to work with special environment variables (__app_id, __firebase_config, __initial_auth_token) when run in a specific collaborative environment. For local development, you will need to manage Firebase initialization and authentication yourself.

Run the Application:

npm start


This will start the development server, and you can view the app in your browser at http://localhost:3000.

How It Works

The application is built as a single-file React application (App.jsx) for simplicity. It uses Firebase for the backend, handling data storage and real-time updates.

State Management: Uses React Hooks (useState, useEffect) for managing component state.

Database: Firestore is used to store tasks, pinned items, and user data. onSnapshot is used to listen for real-time changes.

Styling: Tailwind CSS is used for all styling, providing a utility-first approach for a clean and responsive design.

Notifications: The browser's native Notification API is used for reminders.

Enjoy boosting your productivity with ProTask Suite!
