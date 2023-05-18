# Daily-Expense-Tracker
Configuration and Setup
In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

Open the project in your prefered code editor.
Go to terminal -> New terminal (If you are using VS code)
Split your terminal into two (run the Frontend on one terminal and the server on the other terminal)
In the first terminal

$ cd Fronted
$ npm install (to install Frontend-side dependencies)
$ npm run dev(to start the Frontend)
In the second terminal

cd Backend and Set environment variables in .env
Create your mongoDB connection url, which you'll use as your MONGO_URL
Supply the following credentials
#  ---  Config.env  ---
PORT =5000
MONGO_URL =
# --- Terminal ---

$ npm install (to install backend-side dependencies)
$ npm start (to start the backend)

Technologies used
This project was created using the following technologies.

Frontend
React js - JavaScript library that is used for building user interfaces specifically for single-page applications
React Hooks - For managing and centralizing application state
react-router-dom - To handle routing
axios - For making Api calls
Bootstrap - For User Interface
React icons - Small library that helps you add icons to your react apps
Chart.js - For showing the chart in the app.
Backend
Node js -A runtime environment to help build fast server applications using JS
Express js -The server for handling and routing HTTP requests
cors - Provides a Connect/Express middleware
Mongoose - For modeling and mapping MongoDB data to JavaScript
Dotenv - Zero Dependency module that loads environment variables
Nodemon - To monitor changes to the program code that is being developed

Database
MongoDB - It provides a free cloud service to store MongoDB collections.
