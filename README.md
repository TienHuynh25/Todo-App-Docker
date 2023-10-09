# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.  

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started  

## How to run    
Build the image:    
  $ docker build -t todo-app .  
Run container:    
  $ docker run -dp 127.0.0.1:3000:3000 todo-app  
Open Browser and connect to http://localhost:3000/  
