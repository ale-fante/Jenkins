# Jenkins

https://jenkins.io/
https://docs.docker.com/docker-for-mac
https://docs.docker.com/compose/install/
(animalefante/fresnillo)

- Pull in the Jenkins configuration

docker pull jenkins/jenkins

- An image is a snapshot of a configuration


- To see where docker is saving the files:

docker info | grep -i root

- To know how much space docker is taking:

sudo du -sh  **[Directory]**