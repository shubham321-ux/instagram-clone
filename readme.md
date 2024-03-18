# Instagram Clone Project
This project is a simple Instagram clone that allows users to sign up, log in, post pictures, like pictures, edit their profiles, follow other users, and view posts from users they follow.

## Technologies Used
### Node.js
### Express
### MongoDB
### EJS (Embedded JavaScript)
### Tailwind CSS
### Getting Started
3 To get started with the project, follow these steps:

Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/instagram-clone.git
Navigate to the project directory:
bash
Copy code
cd instagram-clone
Install the dependencies:
bash
Copy code
npm install
Set up MongoDB:

Make sure MongoDB is installed and running on your system.
Create a MongoDB database for the project.
Configure environment variables:

Create a .env file in the root directory of the project.
Add the following environment variables to the .env file:
plaintext
Copy code
PORT=3000
MONGODB_URI=mongodb://localhost:27017/instagram
SESSION_SECRET=your_session_secret
Replace your_session_secret with a secret key for session management.

Start the server:

bash
Copy code
npm start
Open your web browser and navigate to http://localhost:3000 to view the application.
Features
User Authentication: Users can sign up and log in to their accounts securely.
Post Pictures: Users can upload pictures with captions.
Like Pictures: Users can like pictures posted by other users.
Edit Profile: Users can edit their profile information, including their username, bio, and profile picture.
Follow Others: Users can follow other users to see their posts in their feed.
View Feed: Users can view posts from users they follow in their feed.
Folder Structure
The project's folder structure is organized as follows:

config/: Contains configuration files for the application.
controllers/: Contains controller functions for handling requests.
models/: Contains Mongoose models for MongoDB schemas.
public/: Contains static assets such as images and CSS files.
routes/: Contains route definitions for different endpoints.
views/: Contains EJS templates for rendering HTML views.
app.js: Main entry point of the application.
server.js: Express server configuration.
