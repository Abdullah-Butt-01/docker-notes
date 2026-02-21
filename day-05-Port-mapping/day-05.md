# Day 05 - Port Mapping and Run App in Container

## Objective

* Understanding how conatiner ports work and how to map container ports to host

## Commands Practiced

* docker run -d -p 8080:80 --name <name <image_name:tag
	- -d - run in background
	- -p - port

## what I did

* Created folder project inside VM
* Created Dockerfile and built its image
* Ran container with port mapping
* Testing app inside VM and from host using SSH
* Stopped and removed container
* Removed image

## Key Learnings

* -p Host_port:Container_port - for port mapping
