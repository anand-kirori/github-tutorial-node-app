# GitHub Tutorial Node App
Branch - Docker |
Basic node.js app that prints "Hello! This is our first project in GitHub" |
Designed to test dockerfile for building docker images


## Common Commands

Build image
`docker build .`

Tag images
`docker build -t local/node-app-docker .`

List images
`docker images`

Running a Docker image
`docker run -p80:3000 <image-id>`
`docker run -d -p80:3000 local/node-app-docker`

List all running containers
`docker ps`

List all containers (running and stopped)
`docker ps -a`

Scan Docker Images (you must be logged in to docker hub)
`docker scan local/node-app-docker`
