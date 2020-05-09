# full-stack-starter

## All the code that has been done in this repository is coded on Ubuntu 18.04

1. Install Postgres - 

You will find many guide on internet, this is one of the link for reference.
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04

## Some commands for postgres  -

To start the postgres with the default user  `sudo su - postgres`

To create a new db ` createdb dbnamedemo`

To use that db `psql dbnamedemo`

Destroy a database ` dropdb <database_name> `

Reset a database  `dropdb <database_name> && createdb <database_name>`

Some more commands -

```
Starts psql with a connection to dbname. Optionally use another user than current user

In psql:

# \l

List all databases on the server, their owners, and user access levels

# \c <dbname>

Connect to a database named

# \dt

Show database tables

# \d <tablename>

Describe table schema

# \q

Quit psql, return to the terminal

# \?

```


## Make your first hello world app in flask -

How to install Flask - 

```
pip3 install flask
pip3 install flask-sqlalchemy

```

Code is in helloFlask.py file

## How to run your flask application 

```
FLASK_APP=helloFlask.py flask run
```