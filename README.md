# Project 1

Web Programming with Python and JavaScript

This project provides a web application which provides ability to users to leave review about a particular book, selected from database and can see reviews made by other people. This uses a third-party API provided by GoodReads ( another book review website ). This project also provide a API to query for reviews and info about a particular book via its api route.

## USAGE

- Login / Register the user account
- Search for a book via ISBN / Title / Author
- Get details about book and ratings from GoodReads
- Provide a rating and submit a review
- Fetch details about a ISBN using **API ROUTE** ( /api/<isbn> )

## INSTALL 

```
# setup environment variables
$ export FLASK_APP=application.py
$ export DATABASE_URL=''
$ export GOODREADS_API_KEY=''

# clone this repo with git
$ git clone repo
$ cd repo 
$ pip install -r requirements.txt

# now create tables and import data
$ python create.py
$ python import.py

# finally run the application
$ flask run
```

> Note: Mysqlclient is required: [Install MysqlClient](https://github.com/PyMySQL/mysqlclient-python)

Get your DATABASE_URL from your DATABASE Credentials
Get your [GOODREADS_API_KEY](https://www.goodreads.com/api)
