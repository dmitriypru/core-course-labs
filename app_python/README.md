# Web Application: Moscow Time using FastAPI

## Overview
A simple web application built with FastAPI that shows the current time in Moscow.

## Build
1. Clone the repository and navigate to the project directory.
2. Set up a Python virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   
3. Install the required packages:

    ```bash
    cd app_python
    pip install -r requirements.txt

4. Run the application:

    ```bash
    uvicorn app:app --reload

## Usage
* Visit http://127.0.0.1:8000/api/time in your browser to view the current time in Moscow.
* Access the interactive API documentation at http://127.0.0.1:8000/docs.

## Docker

### Building the Docker Image

```bash
   docker build -t dmitriypru/core_course_labs_python:latest .
```

### Pulling the Docker Image

```bash
docker pull dmitriypru/core_course_labs_python:latest
```

### Running the Docker Container

```bash
docker run -p 8000:8000 dmitriypru/core_course_labs_python:latest
```


## Contact

For questions, feedback, or suggestions, please contact [@dmitriypru](https://t.me/dmitriypru).

