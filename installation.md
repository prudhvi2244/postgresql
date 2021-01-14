# Trainer : Raj Prudhvi [Oracle Certified]
# Install PostgreSQL on Windows

* PostgreSQL was developed for UNIX-like platforms, however, it was designed to be portable. It means that PostgreSQL can also run on other platforms such as macOS, Solaris, and Windows.

* Since version 8.0, PostgreSQL offers an installer for Windows systems that makes the installation process easier and faster.


# There are three steps to complete the PostgreSQL installation:

* Download PostgreSQL installer for Windows
* Install PostgreSQL
* Verify the installation

        * https://www.enterprisedb.com/downloads/postgres-postgresql-downloads


# Verify Installation
* There are several ways to verify the PostgreSQL installation. You can try to connect to the PostgreSQL database server from any client application e.g.,  psql and pgAdmin.
* The quick way to verify the installation is through the psql program.
* First, click the psql application to launch it. 
* Second, enter all the necessary information such as the server, database, port, username, and password. To accept the default, you can press Enter.  Note that you should provide the password that you entered during installing the PostgreSQL.
* Third, issue the command SELECT version()

* psql : A terminal-based front-end to PostgreSQL database server.
* pgAdmin : A web-based front-end to PostgreSQL database server.


