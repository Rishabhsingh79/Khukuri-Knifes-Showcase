CRUD Application
This project is a CRUD (Create, Read, Update, Delete) application developed using Java Spring Boot, Postman, SQL, and Apache Tomcat as the web server. The application demonstrates the basic operations on a database and provides an API for interacting with the data.

Features
Create: Add new records to the database.
Read: Retrieve and display records from the database.
Update: Modify existing records in the database.
Delete: Remove records from the database.

Technologies Used
Java Spring Boot: For building the backend RESTful API.
Postman: For testing the API endpoints.
SQL: For managing the database.
Apache Tomcat: As the web server.

Getting Started
Clone the repository:

bash
git clone CRUD Application
This project is a CRUD (Create, Read, Update, Delete) application developed using Java Spring Boot, Postman, SQL, and Apache Tomcat as the web server. The application demonstrates the basic operations on a database and provides an API for interacting with the data.

Features
Create: Add new records to the database.
Read: Retrieve and display records from the database.
Update: Modify existing records in the database.
Delete: Remove records from the database.

Technologies Used
Java Spring Boot: For building the backend RESTful API.

Postman: For testing the API endpoints.

SQL: For managing the database.

Apache Tomcat: As the web server.

Getting Started
Clone the repository:

bash
git clone [https://github.com/Rishabhsingh79/CRUD-project]
Navigate to the project directory:

bash
cd CRUD-application
Set up the database:

Create a new database named crud_db.

Execute the provided SQL script (src/main/resources/db/schema.sql) to create the necessary tables.

Configure the application:

Update the application.properties file with your database CRUDentials.

Run the application:

bash
mvn spring-boot:run
Test the API using Postman:

Import the provided Postman collection (postman/CRUD-application.postman_collection.json) into Postman.

Use the collection to test the Create, Read, Update, and Delete operations.

API Endpoints
Create: POST /api/records
Read: GET /api/records
Update: PUT /api/records/{id}
Delete: DELETE /api/records/{id}

Contributing
Feel free to submit issues or pull requests. Contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.
Navigate to the project directory:

bash
cd CRUD-application
Set up the database:

Create a new database named CRUD_db.
Execute the provided SQL script (src/main/resources/db/schema.sql) to create the necessary tables.
Configure the application:
Update the application.properties file with your database CRUDentials.

Run the application:
bash
mvn spring-boot:run
Test the API using Postman:
Import the provided Postman collection (postman/CRUD-application.postman_collection.json) into Postman.
Use the collection to test the Create, Read, Update, and Delete operations.
API Endpoints
Create: POST /api/records
Read: GET /api/records
Update: PUT /api/records/{id}
Delete: DELETE /api/records/{id}

Contributing
Feel free to submit issues or pull requests. Contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.
