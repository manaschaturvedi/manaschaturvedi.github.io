---
layout: post
title: "Docker notes"
date: 2020-08-14
tags: [notes]
---

- <p>What is Docker: https://www.youtube.com/watch?v=qN1CzLdCq5g</p>

- <p>Docker images are used to extract a container on any server. A Docker image is like a blueprint for creating a container. They contain all the dependencies an application requires</p>

- <p>`docker-compose build` is used to build an image. The web service defined inside a `docker-compose.yml` file uses this image</p>

- <p>Docker can build images automatically by reading the instructions from a Dockerfile. A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image</p>

- <p>Docker Compose reference: https://docs.docker.com/compose/gettingstarted/</p>

- <p>Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration</p>

![TF IDF](/assets/docker-1.png)

- <p>Docker compose file example:</p>

![TF IDF](/assets/docker-2.png)

- <p>In the above example, run docker-compose up in order to start up your application. In this case:
    <br> 1) Compose pulls a Redis image, builds an image for your code, and starts the services you defined. In this case, the code is statically copied into the image at build time
    <br> 2) Enter http://localhost:5000/ in a browser to see the application running
</p>
