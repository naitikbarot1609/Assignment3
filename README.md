- In the webservice directory, created the app.py file which reads the sentence from config.txt and responds with it.

- I have used python:3.9-alpine to reduce the size of image.

- Created a simple text file in the webservice directory with a sentence Assignment 2 By Naitik Barot(8795986)

- In the nginx_lb/ directory, create a nginx.conf file to configure the load balancer.
  nginx.conft

- Created docker-compose.yml file which define the services which is two instances of the web service and one instance of the load balancer.

- I have created network name naitik_network in which containers will run.

- In docker-compose.yml i have used enviorement variables to avoid hardcoding sensitive data in the code or Dockerfiles

- To initiate the service with a single command: docker-compose up --build

- Link for git hub repo - https://github.com/naitikbarot1609/Assignment3
