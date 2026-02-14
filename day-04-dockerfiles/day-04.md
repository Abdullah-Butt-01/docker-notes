# Day 03 - Dockerfile basics + Custom image

## Objective

* Understanding what a dockerfile is, how to create custom image and run it as a container

## Commands Practiced

* docker build -t abdubuntu:1.0 . - building image 
* docker images - check images
* docekr rm1 abdubuntu:1.0 - remove image

## what I did

* Created a dockerfile
* Builded image from the dockerfile
* Ran a container from that image
* Removed the container and image

## Key Learnings

* Dockerfile: a text file that tells Docker how to make your custom image
	- FROM: base image yout container starts with
	- RUN: install packages or run commands during build
	- COPY: move files from your computer into the image
	- CMD: Default command when container runs
