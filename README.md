# Login-Authentication-page

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
SUMMARY

This project is a user login and authentication system which allows new users to create their own accounts and allows existing users to login into their own dashboards.
There is a home page accessible to anyone who visits the webpage. The new users can choose the signup option to create new accounts by entering their personal information and username and password of their choice.
The existing users can go to the login page and type in their credentials to access the user dashboard..
There are dedicated routes and views folders to facilitate easy debugging and editing of code. It can also be easily expanded to hold several webpages.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
TECHNOLOGIES USED :

It is based on Node.js and uses Express.js to create a server. EJS is used as the viewing template. 
The database used is MongoDB. Mongoose library is used to access it. The database used is on the local machine.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
HOW TO RUN IT : 

First you have to install and setup the node environment on your system.
I have provided a sample csv file, you can use it as entries to your Mongo database's collection.
Also change the "MongoURI" to your database's location.
Then open the command client of your operating system and run "npm init".
Fill up the required options and it will install the required libraries.
After that just run "npm start" and your server will start on port 3000.
Open your browser and type "http://localhost:3000".
Make sure you have internet connection to view the Bootstrap CSS.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
FUTURE PROSPECTS

Adding the express-session to manage the session ids in server side cookies and using cookie-parser to maintain client side cookies.
