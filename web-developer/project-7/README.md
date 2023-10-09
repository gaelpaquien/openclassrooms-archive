# Web Developer - OpenClassrooms (Project 7)

## Create a corporate social network

### Skills assessed
 1. Manage a data store using SQL
 2. Customise the content sent to a web client
 3. Implement secure data storage using SQL
 4. Authenticate a user and maintain their session

### Functioning
 1. Frontend framework : Vue.js
 2. Database: MySQL
 3. Server: Node.js
 4. Backend Framework : Express
 5. The project must be coded in JavaScript (so use of the Symfony framework is not allowed).
 
### Mission
 1. Make sure that the web app can connect and disconnect to the application and that the user's session persists while they are connected.
 2. One of the 2 features presented by Groupomania must be 100% functional.
 3. The user must be able to query the required data from SQL and submit these changes to the SQL database.
 4. The connection data must be secure. 
 5. Account creation should be simple and possible from a mobile phone.
 6. The profile should contain very little information so that it can be completed quickly.  
 7. It should be possible to delete the account.
 8. There should be access to a forum where employees can post multimedia content.
 9. Access to a forum where employees post texts must be present.
 10. Users should be able to easily find the latest employee contributions.
 11. The Groupomania communication officer must be able to moderate interactions between employees.
 12. The Groupomania communication manager must be able to display the latest employee contributions.

### Installation of the project
#### Required
 - MySQL
 - Node.js & npm
#### Database
1. Create a local database and name it "groupomania_db_dev".
2. Create a new user with rights to this database.
3. Replace the values of "DB USER" & "DB PASS" in the .env file provided and replace these values with the information of the user with rights on the database created previously. 
If you don't want to use the provided .env file you can use the "master-no-env" GitHub branch, you will then have to follow the installation procedure on the README of this branch. Otherwise you can continue.
#### Application
1. Clone the repository.
2. Insert the ".env" file which contains the environment variables in the root folder of the application.
3. Do an "npm install" directly from the root folder of the application.
4. Do a new "npm install" this time from the "client" folder of the application.
5. Launch the Vue.JS development server with the npm "serve" script from your IDE or use the "vue-cli-service serve" command from a terminal.
6. Launch the backend server with the npm script "dev" from your IDE or the command "nodemon server.js" from a terminal.
