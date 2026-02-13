# Day 03 - More about containers

## Objective

Simulated EC2 Server Deployment

## Commands Practiced

* docker run ubuntu - dies instantly
* docker run -it ubuntu - interactive mode (attach terminal)
* docker run -d ubuntu - detached mode (background)
* docker rm <name - remove a container
* docker container prune - remove all containers
* docker run -dit --name abd ubuntu - name ubuntu container 'abd' running in the background

## what I did

* Created container in background
* Deleted containers
* Named containers
* 

## Key Learnings

* With '-it', docker attaches your terminal. when type 'exit', bash exits.
* Why ubuntu container stops but nginx does not?
	- Ubuntu image: runs bash, exits quickly
	- Nginx image: runs web server, runs forever
