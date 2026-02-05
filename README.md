# Docker ML Lab - Spam Classifier
This repository contains the Dockerized ML lab for PES2UG23CS126.

## How to Run
1. Build the Docker image:
   ```bash
   docker build -t spam-web-app .
Run the container:

docker run -d -p 5000:5000 spam-web-app
Open a browser and visit: http://localhost:5000

Files
app.py - Flask application
templates/index.html - HTML page for web interface
Dockerfile - Instructions to build the Docker image
ML model & vectorizer files 
