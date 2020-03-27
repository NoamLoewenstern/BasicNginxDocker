# docker options:

1. Dockerfile
2. docker-compose
3. cli

# Dockerfile

1. building the image from the 'Dockerfile':
   `docker build -t my-nginx .`
2. running container:
   `docker run --name my-nginx-container -d -p 8080:80 my-nginx`

# docker-compose

`docker-compose up`

# CLI

- if running from linux-terminal:
  `docker run --rm -d -p 8080:80 -v ./src:/usr/share/nginx/html nginx:1.17.9-alpine`
- if running from PowerShell:
  `docker run --rm -d -p 8080:80 -v ${pwd}/src:/usr/share/nginx/html nginx:1.17.9-alpine`
