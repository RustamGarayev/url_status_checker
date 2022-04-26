# URL Status Checker
In this project, we will be using asynchronous requests to get the status codes of the urls defined by each user. 

# Used Technologies
- [Django](https://www.djangoproject.com/)
- [Python](https://www.python.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)
- [Asyncio](https://docs.python.org/3/library/asyncio.html)

## How to start

Simple enough:

`cd _development/`

`docker-compose up --build -d`

`cd ..`

`uvicorn --reload url_status_checker.asgi:application`

`uvicord` is a single-threaded server that can be used to run Django application as an ASGI instead of WSGI. It is used to send asynchronous requests to the defined urls.

## Project dependencies

The project dependency management is based on `pip`. All the required packages are stored in the `requirements.txt` file.
