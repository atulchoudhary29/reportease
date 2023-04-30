# ReportEase

ReportEase is a web application that enables users to effortlessly submit and manage incident reports using a user-friendly interface. With this application, users can create, read, update, and delete incident reports while easily tracking and analyzing data.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
  
 <a name="features"></a> 

  ## 1. Features
- User-friendly interface
- Create, read, update, and delete incident reports
- View incident data in a table format
- Export incident data to other formats (e.g., CSV, PNG)
- Real-time clock in the navigation bar
  
 <a name="installation"></a> 
## 2. Installation

1. Clone the repository:

	```
	git clone https://github.com/username/ReportEase.git
	```
2. Change to the project directory:

	```
	cd ReportEase
	```
3. Install the required dependencies:

- Frontend:

	```
	cd frontend
	npm install
	```
- Backend:

	```
	cd backend
	npm install
	```

4. Install nodemon in backend directory:

	```
	npm i nodemon
	```

<a name="usage"></a>  
## 3. Usage
  
1. Start the backend server:

	```
	cd backend
	npm start or nodemon server

	```
2. Start the frontend server (in a new terminal):

	```
	cd frontend
	npm start
	```
3. Open your browser and navigate to http://localhost:3000 to access the application.

4. Use the navigation bar to access the various features of the application:

- Home: View the homepage with a brief description of the application.
- Form: Create a new incident report using the form provided.
- DataTable: View, update, and delete incident reports in a table format.

5. Update the MongoDB connection string in the backend/config/config.env file:

 - Change the MONGO_URI to your own MongoDB connection string:

 	```
	MONGO_URI=your_own_mongodb_connection_string
	```

 - Make sure to replace your_own_mongodb_connection_string with the actual connection string for your MongoDB instance.
