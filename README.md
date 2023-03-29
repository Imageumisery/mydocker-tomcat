# My first container on docker-tomcat9.0-alpine
Simple container to run your app on tomcat server via docker
My container consists of linux terminal tutorial based on https://github.com/a1qatraineeship/docker_task
Configs on Dockerfile

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Open DockerDesktop
* Clone this repository - $git clone https://github.com/imageumisery/mydocker-tomcat.git
* create sample folder mkdir sample
* cd 'sample'
* compile in it war file
* jar-cvf sample.war
* refactor sample.war into the folder that contains Dockerfile. They must be in the same folder
* cd 'sample'
* $docker build -t mywebapp .
* $docker run -itd -p 8080:8080 mywebapp
* http://localhost:8080/sample read from index.html

# Links
[Sample Tomcat web app](https://tomcat.apache.org/tomcat-8.0-doc/appdev/sample/)
[For more info how to do](https://www.softwareyoga.com/docker-tomact-tutorial/)
