



## Assignment 
This is a code repository
Here I made a Rest API to create,insert,update,delete data.I used a demo data and include Username and age.
I made it using node.js and express.

Here I used Postman (A  tool allows you to design, mock, debug, automated testing, document, monitor and publish the APIs)
I used it for API testing. It is an HTTP client that tests HTTP requests, utilizing a graphical user interface, through which we obtain different types of responses.

#First we download and install the necessary software like node js and postman,then we open visual studio code to check if it is installed or not.
By using 
    node -v command
#Then we create package.json file with node init -y command
#Then made a index.js file which is a starting point of our server.
#Then we install express to make different routes for our api
By
   npm install --save express

Then we start code part first (index.js).Then we describe port and listen function to receive incoming request.
Every time we do some changes we have to stop the server.So to solve the problem we use nodemon
we install nodemon by 
    npm install --savedev nodemon
then we can se the changes in package.json file
Then we start the server by
   npm start
   
#Then we made five different routes  
post to create a user
get to get particular details like i have given data which is for product
delete to delete particular product
patch 

Then I used Postman and try routes

Then we made a controller section
In the routes user.js i have made a user function whic is in the cntroller.

Then We can  check API at http://localhost:5000





