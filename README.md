# Project with multiple Docker containers

The goal of this project is learn how to manage a project with multiple Docker containers, link them with docker-compose for development purposes and deploy them in a production environment using AWS (EB, RDS and ElastiCache).

---

## What I learned?

+ Create a project with independent solutions with a Dockerfile and Dockerfile.dev for each one.

+ Build the Docker images and connect them with docker-compose for a development environment.

+ Use TravisCI to build production level Docker images and upload them to the Docker Hub.

+ Deploy the Docker containers from the Docker Hub to an Elastic Beanstalk (EB) instance.

+ Use the Relational Database Services (RDS) to create and use a PostgreSQL database on AWS.

+ Use the ElastiCache to create and use a Redis in-memory database.

+ Configure an Access Control Policy to connect the Docker containers deployed on the EB to the PostgreSQL database (RDS) and the Redis database (ElastiCache).