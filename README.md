# INTRODUCTION

flask-example3 is a simple example flask app that uses SSL, flask_login, and sqlite. 

- learning Flask.
- kicking off your new project.


## Flask example repositories

Just to explain the repositries and their puprose.  I wanted to keep the examples as seperate repositores - the better to summon up "just enough".

- flask-example0 - basic "text" book example
- flask-example1 - basic example using flask_login and sqlite.
- flask-example2 - basic example that uses "SSL"
- flask-example3 - basic example that uses SSL; flask_login; and sqlite
- flask-example4 - An FLASK example app that uses SSL; flask_login; sqlite and is a little prettier

## INSTALLATION

```bash
git clone https://github.com/tlh45342/flask-example3.git
cd flask-example3
pip install -r requirements.txt
python server.py
```

## STRUCTURE

    ├── README.md                   This document
    ├── requirements.txt            3rd libraries
    ├── server.py                   Wsgi app
    └── app
       ├── __init__.py
       ├── app.py                   Main App
       ├── user
       ├── api
       ├── static                   Static files
       │   └── css
       └── templates                Jinja2 templates
           ├── errors
           ├── frontend
           └── index.html
 
## Version

- 09/26/2021 - Almost ready?

## LICENSE

flask-example2 is licensed under the Apache License, Version 2.0. See LICENSE for the full license text.

## ACKNOWLEDGEMENTS

Many thanks to Python, Flask and other good stacks.
