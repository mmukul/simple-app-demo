## CICD Demo Project

The repository contains a simple Java application which outputs the string
"Hello world!" and is accompanied by a couple of unit tests to check that the
main application works as expected. The results of these tests are saved to a
JUnit XML report.

### Want to access this Project to perform practical demo then *Follow these project steps*

#### Stage-01 : Install JDK and Create a Java Springboot application

#### Stage-02 : Install Jenkins and start Jenkins 
Jenkins Installation Prequuisities  https://www.jenkins.io/doc/book/installing/linux/
1. Installation guide is available here  https://github.com/praveensirvi1212/DevSecOps-project/blob/main/Jenkins_installation.md
1. After installation, install suggested plugins
1. Open Jenkins Dashboard and install required plugins – SonarQube Scanner, Docker Pipeline and Kubernetes
1. go to manage jenkins > manage pulgins > search for plugins > install without restart

## Stage-03 : Install SonarQube

## Stage-04 : Install Docker and Create DockerHub account
1. Create DockerHub account

## Stage-05 : Now go to jenkins > Manage Jenkins > system > configure JDK, maven, Sonarqube, Docker Pipeline and Kubernetes

## Stage-06 : SonarQube integration with Jenkins

## Stage-07 : Add jenkins user to docker group
 ```sh 
sudo gpasswd -a jenkins docker
OR,
groupadd docker
usermod -aG docker jenkins
chmod 666 /var/run/docker.sock
 ``` 
