# Shopping List App

This is a simple **RESTful API** built with Python and Flask. A web service to add, remove and modify items on the shopping list. POST, GET, PUT and DELETE requests sent with appropriate HTTP codes.

- CREATE shopping items,
- READ them,
- UPDATE entries,
- DELETE them.

## Demo

See demo at: http://ancient-sea-11246.herokuapp.com/

The REST API can be accessed via the JavaScript Client or cURL commands / Postman.

## Run

### Docker

Download, build an image with Docker and run on port 5000. The image is also available from my Docker Hub: ```jastr945/shopping:v1.0```

### Traditional way

...Or create a Python virtual environment and run:
```sh
$ export FLASK_APP=app.py
$ flask initdb
$ flask run

```

## Tests
```sh
$ python -m unittest discover

```
