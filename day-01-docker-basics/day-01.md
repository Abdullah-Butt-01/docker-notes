# Day 01 - Docker Basics

## Objective

* Understandig what docker is, its terms and advantages

## Key Learnings
* Docker: Containerization platform, that packages:
	- Your application
	- Dependencies
	- Libraries 
	- into one portable unit, CONTAINER
* VM vs Docker: 
	- VM: Full OS, Docker: Shares host kernal
	- VM: Heavy, Docker: Very lightweight
	- VM: Slow boot, Docker: Starts in seconds
	- VM: More RAM, Docker: uses fewer resources	
* Image - the blueprint
	- like a class
	- contains base OS, installed softwares, app code and config
	- but it is not running, just a template
* Container - the running instance
	- like an object created from the class
	- when you run "docker run ubuntu", docker takes ubuntu image, creates a container and starts it
	- now it consumes CPU and RAM
* Docker Engine - software (the brain)
	- pulls images
	- creates containers
	- runs containers
	- stops containers
	- it runs in the background
* Docker Hub - Image store
	- you don not build everything from scratch
	- "docker pull ubuntu", downloads ubuntu from docker hub

* Why DOCKER?
	- Without docker:
		- Server 1: Ubuntu 20, Node 14
		- Server 2: Ubuntu 22, Node 18
	- app behaves differently, debugging difficulty
	- With docker:
		- Exact Node, configuration
	- Wherever you run it, VM, AWS, Laptop (Environment consistency)
* Other advantages:
	- Isoloation: Containers don not interfare. One app cannot break another easily
	- Micorservices Architecture: Auth service, Payment service, Database, each runs in seperate containers
