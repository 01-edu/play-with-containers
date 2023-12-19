# play-with-conatiners-py

More information about the project
[here](https://github.com/01-edu/public/blob/master/subjects/devops/play-with-containers/README.md)

## Setup

To be able to run this application you need to have the followings installed:

- [Docker engine](https://docs.docker.com/engine/install/)
- [Docker compose](https://docs.docker.com/compose/install/)

To interact with the application, it is recommended to install the following
programs, or any equivalent ones:

- [Postman](https://www.postman.com/downloads/), or any other tool to
  programmatically test API endpoints.
- [DBeaver](https://dbeaver.io/download/), or any other tool to interact and
  visualize the content of a SQL database.

To launch the application, follow the instructions below:

- Create a `.env` file in the root of the project folder as the example
  provided. You can simply `cp .env.example .env`.
- Use the `Makefile` instructions to run, stop and clear the docker containers.

## Docker images

To properly use the provided Docker images, refer to the
[`docker-compose`](./docker-compose.yaml) provided.

Be sure to have a local `.env` file with all the
[`.env.exampl`](./.env.example).

To check which ports are expected to be exposed in each image, check the
fields `expose` or `ports`.
