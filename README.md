# RevatureProject1

# Description
The Bank app is a console-based application that simulates banking operations. A customer can apply for an account, view their balance, and make withdrawals and deposits. An employee can aprove or deny accounts and view account balances for their customers.

# Requirements
1. Functionality should reflect the below user stories.
2. Data is stored in a database.
3. A custom stored procedure is called to perform some portion of the functionality.
4. Data Access is performed through the use of JDBC in a data layer consisting of Data Access Objects.
5. All input is received using the java.util.Scanner class.
6. Log4j is implemented to log events to a file.
7. A minimum of one (1) JUnit test is written to test some functionality.

# Developer Comments
To create this project, I implemented servlets using Java and running the project through a tomcat server. The front end uses mainly JSP pages to check for authentication. The backend uses a Postgres Server to hold data and JDBC to allow the Java programs to communicate with the server and front end web pages.
