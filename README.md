# Registration-Form
This project is a web-based registration form that allows users to register their details, which are then stored in a SQL database. 
The front-end is built using JSP, HTML, CSS, and JavaScript, while the back-end uses SQL for database management.

Features
        User-friendly registration form with fields for name, email, password, date of birth, and gender.
        Client-side and server-side validation to ensure that the user enters valid data.
        Secure password hashing using SHA-256 algorithm.
        Storage of user data in a SQL database, with options for adding, updating, deleting, and retrieving records.
        Display of registered users in a table with the ability to sort and search records.
Technologies Used
        JSP (JavaServer Pages) for dynamic web page generation
        HTML, CSS, and JavaScript for front-end design and interactivity
        SQL (Structured Query Language) for database management
        Apache Tomcat web server for hosting the application
Requirements
        Java JDK 8 or higher
        Apache Tomcat 8.0 or higher
        MySQL or any other SQL database server
Installation
        Clone the repository to your local machine.
        Open the project in a Java IDE and set up the database connection parameters in the database.properties file.
        Run the register.sql script in your SQL database server to create the required table and schema.
        Build the project and deploy the WAR file to Apache Tomcat web server.
Usage
        Access the application by navigating to http://localhost:8080/registration-form/.
        Fill in the registration form with valid data and submit the form.
        View the registered users by clicking the "View Users" button.
