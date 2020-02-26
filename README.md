# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into three parts:
1. [The Simple Frontend](/udacity-c3-frontend)
A basic Ionic client web application which consumes the RestAPI Backend. 
2. [The RestAPI Feed Backend](/udacity-c3-restapi-feed), a Node-Express feed microservice.
3. [The RestAPI User Backend](/udacity-c3-restapi-user), a Node-Express user microservice.

### Github Link https://github.com/Amr-Reda/Udagram-App-Microservices

## Docker hub images
- [Frontend Image](https://hub.docker.com/repository/docker/amrreda88/udacity-c3-frontend)
- [RestAPI Feed Backend Image](https://hub.docker.com/repository/docker/amrreda88/udacity-c3-feed)
- [RestAPI User Backend Image](https://hub.docker.com/repository/docker/amrreda88/udacity-c3-user)
- [Reverse Proxy Image](https://hub.docker.com/repository/docker/amrreda88/reverseproxy)

## Installation
1- export the following environment values to your computer 
```
POSTGRESS_USERNAME=<your-postgres-username>
POSTGRESS_PASSWORD=<your-postgres-password>
POSTGRESS_DB=<your-postgres-database-name>
POSTGRESS_HOST=<your-postgres-host>
AWS_REGION=<your-aws-region>
AWS_PROFILE=<your-aws-profile>
AWS_BUCKET=<your-aws-s3-bucket>
JWT_SECRET=<your-jwt-secret>
``` 

2- using terminal open directory `udacity-c3-deployment/docker/`

3- run `docker-compose up`