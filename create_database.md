# Trainer : Raj Prudhvi [Oracle Certified]
# CREATE Database

# PostgreSQL provides two ways of creating a new database −

* Using CREATE DATABASE, an SQL command.
* Using createdb a command-line executable.

# Using CREATE DATABASE
* This command will create a database from PostgreSQL shell prompt, but you should have appropriate privilege to create a database

# The basic syntax of CREATE DATABASE statement is as follows −

        * CREATE DATABASE dbname

# Using createdb Command
* PostgreSQL command line executable createdb is a wrapper around the SQL command CREATE DATABASE. The only difference between this command and SQL command CREATE DATABASE is that the former can be directly run from the command line and it allows a comment to be added into the database, all in one command.

* Open the command prompt and go to the directory where PostgreSQL is installed. Go to the bin directory and execute the following command to create a database.

        * createdb -h localhost -p 5432 -U postgres testdb
        * password ******


* To check list of databases use the following command

        * \l

