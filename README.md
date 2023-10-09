# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.  

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started  

## How to run    
Build the image:    
  $ docker build -t todo-app .  
Run container:    
  $ docker run -dp 127.0.0.1:3000:3000 todo-app  
Open Browser and connect to http://localhost:3000/  
<img width="1512" alt="Screenshot 2023-10-09 at 4 10 54 PM" src="https://github.com/TienHuynh25/Todo-App-Docker/assets/86528079/ef1645f5-3b81-4dea-9af9-fb2d8f600e6b">
