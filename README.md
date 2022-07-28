# Udagram Image Filtering Application

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

## Project Goal

In this project;
- The Udagram application was refactored from a monolith application to microservices
- Each microservice was set up to be run in its own Docker container
- A Travis CI pipeline to push images to DockerHub
- The DockerHub images was pushed to the Kubernetes cluster
- Autoscaling group was also configured for all running pods

## Prerequisites

- Git
- Node.js
- PostgreSQL client
- Ionic CLI
- Docker
- AWS CLI
- kubectl

