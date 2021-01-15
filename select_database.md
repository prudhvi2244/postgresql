# Trainer : Raj Prudhvi [Oracle Certified]
# SELECT Database

* You can select the database using either of the following methods −

    * Database SQL Prompt
    * OS Command Prompt

# Database SQL Prompt

* You can check the available database list using \l
        
        postgres-# \l

* Now, type the following command to connect/select a desired database; here, we will connect to the college database

        postgres=# \c testdb

# OS Command Prompt
* You can select your database from the command prompt itself at the time when you login to your database

        psql -h localhost -p 5432 -U postgress college
        Password for user postgress: ****



