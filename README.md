# Django + gRPC + Docker

This project is a simple [Django](https://www.djangoproject.com/) application based on gRPC. [gRPC](https://grpc.io/) can efficiently connect services in and across data centers with pluggable support for load balancing, tracing, health checking and authentication.

## Project Structure

The project is split into two parts:

1. __Backend gRPC__: Django web application online retail usecase).

2. __Dockerize the Django app__: Docker, Python, and Gunicorn web server.

### Local Environment Instructions

#### Installation

The requirements.txt file contains the required pip packages.
```
$ pip install -r requirements.txt
```

#### Set up the Django project
Clone the repository, and navigate to the downloaded folder. 
	```
	git clone https://github.com/nalbert9/django_grpc.git
	```
#### Run the project on local
```
$ cd online_retail
$ python manage.py runserver
```

#### Run the project with Docker
