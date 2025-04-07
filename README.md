### Book creating

## About my aplication:
This application is a simple manager list for books, built using Node.js and Express.js. You can create, update, and delete books in this application. User interface is very helpful

## Run app step by step:
1. Clone repository:
    git clone  https://github.com/00022067/BookReviewCourseWork

2. Navigate project:
    cd   name of project   main-list-app

3. Install dependencies by running:
    npm install

4. Start the server:
    npm run start or npm run start:watch for watching environment
    

5. To test the API, open an endpoint like
https://bookreviewcoursework-1.onrender.com/api/main in your browser or Postman.


## Application Dependencies:
The application relies on the following dependencies:
- Express: for building the server application.
- EJS: for rendering content in HTML.
- JOI: validation.
- CORS: to run application in frontend part.

Install these dependencies using the command:
    npm install express ejs cors dotenv joi




## Application Structure Overview
- Configuration
app.config.js: This file extracts the port number specified in the .env file.
- Controllers
controller.js: This module defines various functions to manage HTTP requests related to books within application.
- MAIN_PAGE: Displays the main page (main.ejs) and retrieves books from books.json.
CREATE_BOOK: Manages the creation of new books, ensuring no duplicates are added to books.json.
UPDATE_BOOK: Modifies existing books based on their IDs, updating the information stored in books.json.
DELETE_BOOK: Removes books based on their IDs, updating books.json accordingly.
- Middleware
This directory hosts error handling and validation middleware crucial for maintaining the application's reliability and security.
- Database
  books.json: Contains an array for interacting with data stored in books.json, handling data persistence and retrieval.
- Public
Stores static files (e.g., CSS, JavaScript) used in EJS views.
- Routing
routes.js: Defines the application's routes, mapping specific controller functions to handle each route.
- Schema
creator.schema.js: Houses Joi schemas for validating book creation requests, leveraging Joi
- Additional Helpers
helpers: Contains helper functions facilitating read and write operations on books.json.
- User Interface
views: Stores the view template (main.ejs) responsible for rendering the main list interface, serving as the presentation layer of the application.
- Main Root File
main.js: Contains JavaScript code enhancing the functionality of the server as a whole.


Github Account: https://github.com/00022067/BookReviewCourseWork in here every push and commits showed properly you can clone it