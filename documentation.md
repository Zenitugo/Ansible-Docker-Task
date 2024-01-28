# ANSIBLE-DOCKER EXECUTION

This is just a simple playbook used to pull docker images and create containers from the image.

## STEP 1: PULL
The first section of the playbook is focused on pulling the latest docker image of nginx, postgressql and jenkins.

## STEP 2: RUN
The second step of the playbook creates a docker container from the images pulled. The port of the docker host and the docker container was mapped so that it can be accessed from a web browser.

### Image of the nginx server
![nginx](./images/docker-nginx.png)

### Image of Jenkins server
![jenkins](./images/jenkins.png)



