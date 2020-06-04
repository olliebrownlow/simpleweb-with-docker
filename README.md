# SimpleWeb

### Introduction

Veeeeeeeeeeeeery basic express/node.js web app that runs in a docker container.

Simpleweb is an express app with one route where the phrase _Hi there_ is printed on your web browser of choice.

### Getting started

\*\*You must be able to run [docker](https://www.docker.com/get-started) on your computer\*\*

- Clone this repository to your local machine
- Navigate into the simpleweb directory `cd simpleweb`
- Build the Dockerfile to create the image `docker build .` and save the image-id
- Run the image with port mapping `docker run -p 8080:8080 <image-id>`
- Open localhost:8080 in your favourite browser
