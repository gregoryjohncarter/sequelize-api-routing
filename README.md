## e-commerce back end

## Installation
Make sure you have Node.js and MySQL installed. Navigate to the root directory and type 'npm install' to add MySQL2, dotenv, and Sequelize packages.

## Usage
Create a .env file in your directory which follows the structure of 

DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='your MySQL PW here'

Login to the MySQL shell while navigated to the root directory with 'mysql -u root -p'. Type 'source db/schema.sql'. Quit from the MySQL shell. Type 'npm run seed' to seed data to the database.

Now use the provided routes such as 'api/categories', 'api/categories/#id', 'api/tags', 'api/#tags', etc. with the associated GET, POST, PUT, or DELETE requests. Use Insomnia API client to test more than just the basic get requests (you may test these in a browser by typing in the preceding sample endpoints at 'http://localhost:3001/endpoint_here'). Reference the code provided in the 'models' and 'routes/api' directories for complete endpoints, API request information, and valid JSON req. parameters.

To test using Insomnia, navigate to root and type 'npm start' to start the Express.js server. You may then initiate your requests via the app for testing purposes. 

## Technologies
MySQL2, Sequelize, Node.js, Express.js, Insomnia API client, dotenv

# Demonstration videos
<a href="https://drive.google.com/file/d/16E6R2Ynz10J6yT0Ttp3A2Dhcid7IxGm4/view?usp=sharing" target="_blank">Video 1</a>
<a href="https://drive.google.com/file/d/1Rz2zdPCVRZ3heExvZSINKYnAEDpAH-nu/view?usp=sharing" target="_blank">Video 2</a>

