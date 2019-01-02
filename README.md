# node-login
Registration and login app using Node.js and Passport (Traverse Media).

This application demonstrastes simple authentication. Users can register, login, logout, and view their dashboard. This is more of a boiler plate for further development. 

## Tech Stack

This application uses a Mongo database. Specifically I set up a free cluster in Mongo's Atlas cloud resource to store users information. In addition the CRUD operations are handled with the OBject Data Modeling Library Mongoose.

 Node.js 10.15.0 has been used to set up the routes and general application logic. We use the Express framework to organize our code into an MVC architecture. EJS partials are used to display any error messages while validating registering and logging in. 

Bootstrap theme for responive design: https://bootswatch.com/superhero/ 

## Security

Passwords are encrypted and stored in the MongoDB using bcryptjs. Passport is used to handle authentication for the dashboard link to make sure users can't view restricted resources while logged out. 

##Deployment

This has not yet been deployed or hosted in anyway. The project was developed using VSCode on a windows machine. If you clone the project and run "npm run dev"...you can find the project by navigating to your localhost at port 5000.



Tutorial can be found at: https://www.youtube.com/watch?v=6FOq4cUdH8k 