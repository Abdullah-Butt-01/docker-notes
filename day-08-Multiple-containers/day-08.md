# Day 07 - Dockerized App onn EC2 (VM)

## Objective

* Take a small app, dockerize it, deploy on EC2, and access via browser

## Commands Practiced

* docker logs <container_id -  shows what the container printed (Errors, startup messages)
	- debugging tool if container fails

## What I did

* Connected VM to host using SSH
* Created project folder and files:
	- Dockerfile
	- app.py
	- requirements.txt
* Used docker logs command to check what container is saying
* Container ran and tested on the browser

## Problems Faced

* DEPRECATED: the legac builder is deprecated
* Failed to connect to localhost	 

## How I solved

* Connected to Internet and it worked
	- Corrected Dockerfile and app.py
* Corrected mistakes in files
