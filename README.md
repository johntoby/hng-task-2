# hng-task-2
A simple python flask application that returns a random number between 1 and 100. Every time you open the application page, or refresh the page, it returns a different random number. 
The application is written in python using the flask framework. 
The Dockerfile has been prepared to dockerize the application using a distroless python container base image. 
To run the application, run the following commands: 

```bash
$ docker run -t johntoby/flask-random-number-app .
$ docker run -p 5000:5000 johntoby/flask-random-number-app

```end

- Remember to expose port 5000 on your security group if running the application on a Virtual machine like EC2 instance. 
