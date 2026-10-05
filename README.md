# Django Notes App - DevOps Portfolio Project
This is a simple notes app built with React and Django.

**CI/CD Status:** ![CI/CD Pipeline](https://github.com/Tejas-Shende056/Notes-app/actions/workflows/ci.yml/badge.svg)

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
