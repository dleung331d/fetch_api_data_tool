# Project overview

The objective of this project is to allow user to perform the following functions
- request data from a web API and store as JSON file
- load JSON file to database 
- create JSON file by querying database via SQL

This project is still working in progress and has only been tested with the following API
- https://the-one-api.dev/

# Setup

Clone this repo

---
Create virtual environment

% python -m venv venv  

% source venv/bin/activate  

---
Install requirements

% pip install -r requirements.txt 

---
Sign up for your own API access token on https://the-one-api.dev/ and save the toekn in a text file like this. 

Bearer "Your API key"

For example

Bearer awegth32tyta83

---
Run program in interactive mode

% python project.py

---

## Request API
User needs to provide an API URL and an access token if required by the API.

The API response will be displayed to the user.  The user can choose how to map the data into a new table in database.
