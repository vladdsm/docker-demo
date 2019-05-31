Docker Containers for Reproducible Research
========================================================
author: Vladimir Zhbanko
date: 14.05.2019
autosize: true

What is it?
=============================

![image](https://oer.gitlab.io/oer-on-oer-infrastructure/figures/OS/containers.png)

Advantages
=============================

* Efficient
* Portability
* Reproducibility
* Automated

Disadvantages:
=============================
* Persistent Data Storage
* GUI
* Speed (if required)

Examples of Dockerfiles
=============================

## set up custom R-Studio IDE in a container
* GitHub repository: https://github.com/vladdsm/docker-r-studio
* DockerHub image with auto-build: https://cloud.docker.com/u/vladdsm/repository/docker/vladdsm/docker-r-studio

## set up base R template in a container
* GitHub repository: https://github.com/vladdsm/docker-r-h2o
* Dockerhub image with auto-build: https://cloud.docker.com/repository/docker/vladdsm/docker-r-h2o

## examples
* example of adding R markdown https://github.com/vladdsm/docker-r-r
* example of running R script: https://github.com/vladdsm/docker-r-s

Useful resources
========================

Use r with docker general info ⇒ this is just amazing tutorial!!!
https://ropenscilabs.github.io/r-docker-tutorial/

Run R script in the docker container:
https://www.r-bloggers.com/running-your-r-script-in-docker/ 

