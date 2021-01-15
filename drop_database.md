# Trainer : Raj Prudhvi [Oracle Certified]
# DROP Database

# There are two options to delete a database 

    * Using DROP DATABASE, an SQL command.
    * Using dropdb a command-line executable.

# Using DROP DATABASE
* This command drops a database. It removes the catalog entries for the database and deletes the directory containing the data. It can only be executed by the database owner. This command cannot be executed while you or anyone else is connected to the target database (connect to postgres or any other database to issue this command).

        Syntax
        DROP DATABASE [ IF EXISTS ] name

# Using dropdb Command
* PostgresSQL command line executable dropdb is a command-line wrapper around the SQL command DROP DATABASE. There is no effective difference between dropping databases via this utility and via other methods for accessing the server. dropdb destroys an existing PostgreSQL database. The user, who executes this command must be a database super user or the owner of the database.

        dropdb  [option...] dbname

        dropdb -h localhost -p 5432 -U postgress testdb
        Password for user postgress: ****

