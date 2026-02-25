# Day 08 - Multiple contiainers

## Objective

* Stop and Restart Container
* Change flask app message
* Run Multiple Containers

## Commands Practiced

* docker prune - remove unwanted containers and images
	- docker container prune
	- docker image prune -a

## What I did

* Created, stopped and restarted containers
* Changed flask app message, created new image, new container
* Checked in the browser
* Ran multiple containers

## Problems Faced

* Token for Github expired, and problem with connecting to Github. 403 error	 
* Problem when creating new flask image from Dockerfile (Didn't used '.' at the end of docker build)

## How I solved

* Created token with repo permissions checked
* Used dot at the end to use the current directory
