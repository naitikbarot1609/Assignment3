# Assignment 3: Advanced Containers

This project uses a flask containers in he webservice directory which reads the sentence from config.txt and responds with it.

## Pre reqs

Ensure that you have the pre reqs installed by checking using the following:

```bash
docker -v
```

```bash
docker compose -v
```

## Configuration

In the nginx_lb/ directory, create a nginx.conf file to configure the load balancer. nginx.conft

### Environment Variables

use `mv .env.example .env` to rename the `.env` file. Then fill out the file with the correct information.

## Running the Project

To initiate the service with a single command:

```bash
docker-compose up --build
```

## Bring down the project

```bash
docker compose down
```
