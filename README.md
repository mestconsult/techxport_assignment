# TechXport Assignment 2 (Node JS)

We have taken a look at Node JS and how to connect our Node JS application to a mongo db database. For this assignment, use the mongoose library to create a user model and then create routes for adding a new user, updating a user, checking if a user exists in the database and a route that is called to delete the user.
*The assignment should be submitted by **Monday, 12th October**.

## Details of the assignment
1. Create a new file in the models folder called user.js
1. Open the new user.js file and use mongoose to create a new Schema called User.  The User schema should have the following fields: firstname, lastname, email, password, and profileImageUrl
1. Export the User schema from the user.js file as a mongoose model
1. Open the routes.js file and create the following routes:
    1. /users/create 
    1. /users/update
    1. /users/delete
    1. /users/authenticate
    
1. The /users/create route should use a **post**, the /users/update route should use a **put**, the /users/delete route should use a **delete** and /users/authenticate route should use a **post**


## Submiting the assignment
Zip folder containing all files and email to nelson@meltwater.org

The assignment should be submitted by **Monday, 12th October**.
