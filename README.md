# ChitChatopia


Welcome to ChitChatopia! 

Getting Started

To run this project, you will need to have Node.js installed on your machine. This project has been developed and tested on Node.js version 16, so please ensure that you have the node version 16 installed before proceeding.

To install the necessary dependencies, Run the following command in your terminal:

npm install 

Running the Application

To run the frontend, navigate to the project root directory and run the following command in your terminal:

npm start

This will start the frontend server and you can access the application by navigating to http://localhost:3001 in your browser.

To run the backend, open a new terminal window, navigate to the project root directory, and run the following command:

>npm install

Change the following database connections in .env files as per your system:

DB_HOST=127.0.0.1

DB_USER=postgres

DB_PASSWORD=Mnblkjpoi098!

DB_DATABASE=chat_app
 
 
Then, Run the following 2 commands on backend termainal

>npx sequelize-cli db:migrate

>npx sequelize-cli db:seed:all

Start the server.
>npx nodemon index.js

This will start the backend server and you can access the API by sending HTTP requests to http://localhost:3000.

Contributing

If you would like to contribute to this project, please feel free to submit a pull request.


