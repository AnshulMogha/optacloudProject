# optacloudProject
Setup Instructions backend

Step 1: Set up environment variables
Open the .env file in the root directory of your project.

PORT=5000
DB_PASSWORD=asajhahshahshahshahshas
DB_CONNECTION_STRING=mongodb+srv://anshulmogha3000:<password>@canucode.44ggwdt.mongodb.net/optacloud?retryWrites=true&w=majority&appName=CanUCode

Make sure that you have used your own database string and password in the same format mention above:

Step 2: Install dependencies
Run the following command in your terminal to install all necessary dependencies:

npm install

Step 3: Start the server
Once the installation is complete, run the server using the following command:

node server.js

Step 4: Check for Errors
Check the terminal (CMD) for any error messages. If you see no errors, the server is set up successfully.

Note:
The app may contain some bugs due to limited time for development.


How to Run the Frontend Application
Step 1: Install all the necessary packages

==> npm install

This command will install the required dependencies listed in the package.json file.

Step 2: Run the app in development environment to avoid potential issues

npm run dev

After running this command, follow the URL shown in the terminal to access the app.

Note:
Backend Server Requirement: The application requires an active backend server. Make sure the backend server is running to ensure the app works correctly.

Important Routes

Home Route: http://localhost:5173/
Manage Addresses Route: http://localhost:5173/addresses

Note:
The app may contain some bugs due to limited time for development.


