# Web Developer - OpenClassrooms (Project 6)

## Build a secure API for a food review application

### Skills assessed
 1. Implement a logical data model in accordance with the regulations.
 2. Store data securely.
 3. Implement CRUD operations in a secure manner.

### Functioning & constraints
 1. Framework: Express
 2. Server: NodeJS 
 3. Database: MongoDB
 4. All database operations must use the Mongoose package with strict data schemas.
 5. The API must work perfectly with the frontend of the project, there must be no regressions on the frontend.
User data must be protected, both on the API side and on the database side with masking methods.

### Security requirements
 1. The API must comply with OWASP standards.
 2. The API must comply with the RGPD. 
 3. The users' password must be encrypted.
 4. 2 types of administrator rights to the database must be defined: access to delete or modify tables, and access to edit the database contents.
 5. The security of the MongoDB database (from a service such as MongoDB Atlas) must be done in such a way that the validator can launch the application from his machine.
 6. Authentication is enforced on the required routes.
 7. Passwords are stored securely.
 8. Database email addresses are unique and an appropriate Mongoose plugin is used to ensure their uniqueness (the plugin will also report database errors).
 
### Installing the API
1. Download the project backend.
2. Add the environment variables in a new file that must be created and named ".env" in the root folder of the backend.
3. Launch the project backend with the following command "nodemon server"

--- --- ---

## Application frontend
https://github.com/OpenClassrooms-Student-Center/dwj-projet6