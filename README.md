# File Sharing App
A robust file-sharing application developed using the MERN stack (MongoDB, Express, React, Node.js).

## Features
#### User Authentication: Secure login and registration using JWT.
#### File Upload/Download: Easily upload and download files with progress tracking.
#### File Sharing: Share files with others through unique, time-limited links.
#### Responsive Design: Optimized for both desktop and mobile devices.
#### Drag and Drop: Intuitive drag-and-drop interface for file uploads.
#### File Previews: Preview images and documents before downloading.

## Technologies Used
### Frontend:

##### React: Component-based UI development.
##### Redux: State management.
##### React Router: Client-side routing.
##### Bootstrap: Responsive design and styling.

### Backend:

##### Node.js: JavaScript runtime environment.
##### Express: Web framework for Node.js.
##### MongoDB: NoSQL database.
##### Mongoose: ODM for MongoDB.
##### JWT: JSON Web Tokens for authentication.

## Installation
Prerequisites
Node.js and npm installed
MongoDB installed and running
Setup
Clone the repository:

sh
Copy code
git clone https://github.com/yonas-fsaha/File-sharing-app-MERN-stack.git
Navigate to the project directory:

sh
Copy code
cd File-sharing-app-MERN-stack
Install server dependencies:

sh
Copy code
cd server
npm install
Install client dependencies:

sh
Copy code
cd ../client
npm install
Configure environment variables:
Create a .env file in the server directory with the following:

env
Copy code
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Running the Application
Start the server:

sh
Copy code
cd server
npm run dev
Start the client:
Open another terminal, navigate to the client directory, and run:

sh
Copy code
cd ../client
npm start
Access the application:
Open your browser and go to http://localhost:3000.

Project Structure
client: Contains the React frontend.
public: Static files.
src: Source code for React components, Redux setup, and utilities.
server: Contains the Express backend.
config: Configuration files.
controllers: Request handlers.
models: Mongoose models.
routes: API routes.
middlewares: Custom middleware functions.
utils: Utility functions.
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.
