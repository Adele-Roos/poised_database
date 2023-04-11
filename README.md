# poised_database
Database projects

DESCRIPTION

The Poised database project is a relational database designed to manage project information for a construction company. The database allows the company to track project details, such as project names, dates, budgets, contractors, and architects. The project information can be easily queried and updated as needed.

TECHNOLOGIES USED

MySQL database management system
SQL programming language
Java programming language
JDBC driver for MySQL

INSTALLATION

To install and set up the Poised database project, follow these steps:

1. Install MySQL database management system on your local machine.
For Windows:
Download MySQL Installer from (https://dev.mysql.com/downloads/installer/)
and execute it. Choose the appropriate Setup Type for your system.
For Mac:
Download the MySQL DMG Archive from the MySQL website (https://dev.mysql.com/downloads/mysql/).
Your operating system should be automatically detected, however, if it is not:
a. Select the General Available (GA) Releases tab.
b. In Select Operating System choose macOS

3. Create a new MySQL database named "poised_db" using the MySQL command line or a graphical user interface.
   Grant priviledges to user to access the database and verify that the database is created and that access is granted.

4. Execute the "poised_db.sql" script in the "sql" directory to create the database schema and tables by entering this in the commandline:
    source /path/to/sql/poised.sql; 
   Replace "/path/to/sql/" with the path to the "sql" directory in the program files for example: source C:/Users/JohnDoe/ProgramFiles/sql/poised.sql;

5. Go to the Oracle site and open the Java SE download page (https://www.oracle.com/za/java/technologies/downloads/). Install Java Development Kit (JDK) 
   on your local machine.

6. Set up the Java development environment, this project was done using Eclipse (https://www.eclipse.org/downloads/packages/installer). Add the JDBC driver         
   for MySQL to the classpath. You can download the MySQL Connector/J driver from the MySQL website.
   
7. Configure the program: In the program code you will need to update the database connection information to match the database set up on the local       
   machine. Update the database URL: jdbc:mysql://localhost:port/database_name as well as the username and password.
   
8. Run the program.
 

USAGE

To use the Poised database project, follow these instructions:

Start the Java application.
Connect to the MySQL database using the JDBC driver.
Use the Java user interface to add, edit, or view project information.

EXAMPLES

Here are some examples of how to use the Poised database project:

To add a new project, select the "Add Project" option and follow the prompts to fill in the project details.
To update any table, select the "Update Project" option. Type in the table name you want to update. Choose the field option, fill in the updated information and select the project id you want to make the changes to.
To delete a project, select the "Delete Project" option and enter the project id to remove that project.
To finalise a project, select the "Finalise Project" option. Next choose option 'yes' or 'no' to update the final fee before being prompted to enter the completion date. Type 'Finalised' to confirm. Enter the project id that needs to be finalised.
To search for projects in progress, select the "Search Projects in Progress" option.
To search for projects past deadline, select the "Search Projects Overdue" option.
To view projects, select the "Search All Projects" option and choose option to view by product id or to view by product name.
To exit to menu, select "EXIT" option.

CONTRIBUTING

Contributions to the Poised database project are welcome. To contribute, please fork the repository, make your changes, and submit a pull request.

LICENSE

The Poised database project is licensed under the MIT license.

CONTACT

If you have any questions or feedback about the Poised database project, please contact us at info@poised.com.
