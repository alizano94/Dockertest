# README

This README contains the information realted to the TODO app implemented on Rails and Dockerized
Be sure to have already intalled both Docker Engine and Docker Compose, you can check that on the links porvided:
https://docs.docker.com/get-docker/
https://docs.docker.com/compose/install/

In order to run the app, follow this comands. 

Once you check that run:

sudo docker-compose up

Open youre favorite browser and type:

http://localhost:3000/

In order to deploy the app make us of the nginx-deployment.yaml file.

run: kubectl apply -f nginx-deployment.yaml
 
