 
- We’ll create our Django project by running the command below in the Terminal (macOS/Linux) or PowerShell on Windows:

 docker run -v ${PWD}/app:/app -w /app python:3.9-alpine sh -c "pip install Django==3.2 && django-admin startproject app ."

- Once these changes are made, you can test them by running the following in the Terminal or Command Prompt window:

docker-compose build
docker-compose up