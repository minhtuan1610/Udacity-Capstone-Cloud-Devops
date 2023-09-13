# Udacity Capstone Project

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/minhtuan1610/Udacity-Capstone-Cloud-Devops/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/minhtuan1610/Udacity-Capstone-Cloud-Devops/tree/master)

## Project Overview

Capstone project

## Propose and Scope the Project

1. My pipeline
    | Build --> Push --> Deploy
2. Use Circle CI for Continuous Integration phase.
3. Deployment type: Rolling deployment.
4. Application: a HTML file application using nginx

## Project step
1. Build pipeline using CircleCI
    - Using the config file in the link: ```.circleci/config.yml```
2. CircleCI
    - build: Create the "squirtle-app" application, run lint the dockerfile.
    - push-docker: Build image and push it into the Dockerhub.
    - deploy: Deploy application using AWS Kubernetes as Service: ```eksctl``` and ```kubectl```.
3. Run app
    - Use the link in the section ```Url app``` to access the web.

# Url app
http://a6d2975775ba94d929517fcb33ce283e-1113897778.us-east-1.elb.amazonaws.com:8080/
# Github
https://github.com/minhtuan1610/Udacity-Capstone-Cloud-Devops

