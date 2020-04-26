# docker-demo

## Purpose

Illustrate few use cases about using Docker Containers for Data Science and Reproducible Research

## Advantages:

* Portability
* Reproducibility
* Automated builds

## Disadvantages:

* Persistent Data Storage
* GUI

## Examples of Dockerfiles

* set up custom R-Studio IDE in a container. Added custom packages and h2o open-source platform: https://github.com/vladdsm/docker-r-studio
* set up base R template. Added custom packages and h2o open-source platform: https://github.com/vladdsm/docker-r-h2o
* example of adding R markdown: https://github.com/vladdsm/docker-r-r
* example of running R script: https://github.com/vladdsm/docker-r-s
* example of R plumber API: https://github.com/vladdsm/docker-r-plumber
* example of R ShinyApp: https://github.com/vladdsm/docker-r-shiny
* example of R ShinyApp developed in a Docker Container with {golem} framework: https://github.com/vladdsm/trackpack
* PLANNED example of multi container application (ShinyApp + database): 

# Docker compose

Service to run multi container applications:

## Useful commands on Docker compose

* Check version: `docker-compose version`
* Start service: `docker-compose up` - must be in the same folder as `docker-compose.yml` file
* Stop service: `docker-compose down` 
* Command to run docker compose file: `docker-compose up -d`
* Command to check all processes: `docker ps`
* ... scale a service: `docker-compose up -d --scale`

## Useful resources

Use r with docker general info ⇒ this is just amazing tutorial!!!
https://ropenscilabs.github.io/r-docker-tutorial/

Run R script in the docker container:
https://www.r-bloggers.com/running-your-r-script-in-docker/ 



