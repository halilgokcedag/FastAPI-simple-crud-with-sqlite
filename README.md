# FastAPI-simple-crud-with-sqlite

### About The Project
This simple project is adapted from [SQL (Relational) Databases](https://fastapi.tiangolo.com/tutorial/sql-databases/). Original tutorial includes only Create and Read operations. Delete operation has been added.

## Built With

* Python 3.10
* FastAPI
* SQLite
* Docker

## Getting Started

### Prerequisites

Please req.txt file for the required packages. Install the packages using pip.

### Deployment

1. Clone the repo and go to the directory FastAPI-simple-crud-with-sqlite.

2. Run the following commnad
```
uvicorn sql_app.main:app --reload
```

3. You can open your browser at http://127.0.0.1:8000/docs .You will be able to interact with your FastAPI application, creating, reading and deleting data from a SQLite database


### FastAPI in Containers 

#### Build the Docker Image

It is recommended to build the image in a freshly cloned directory.

1. Build your FastAPI image.
```
docker build -t fastapi .
```

2. Start the Docker Container.
```
docker run -d --name mycontainer -p 80:80 fastapi
```

3. Check it

You should be able to check it with this URL: http://127.0.0.1/docs