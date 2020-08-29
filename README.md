# Dockerized Angular 10 App (with Angular CLI)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.3.

### Build docker image
````bash
$ docker build -t angular-docker . 
````

### Run the container

````bash
$ docker run -d -p 8000:80 angular-docker
````

The app will be available at http://localhost:8000
