# FastAPI-simple-crud-with-sqlite

### About The Project
This simple project is adapted from [SQL (Relational) Databases](https://fastapi.tiangolo.com/tutorial/sql-databases/). Original tutorial includes only Create and Read operations. Delete operation has been added.

## Built With

* Python 3.10
* FastAPI
* SQLite

## Getting Started

### Prerequisites

Please req.txt file for the required packages. Install the packages using pip.

### Deployment

1. Clone the repo and go to the deployment directory.

2. Run the following commnad
```
uvicorn sql_app.main:app --reload
```

3. You can open your browser at http://127.0.0.1:8000/docs
You will be able to interact with your FastAPI application, creating, reading and deleting data from a SQLite database
