# installation-step-jenkins on Ubuntu OS 

Guys sometime we get lot of  error during jenkins installation
- jenkins pacakge not found even if you update your machine many time


Pleae follow the blow step for proper installation 
- t2.micro is working but better t2.medium for jenkin
- allways select latest version of OS
- console the machine
- use the following command to be update to date
```git
sudo apt update -y
sudo apt upgrade -y
sudo init 6      # to restart the machine 
```
- install  java
```git
java -version  # check the jaa version
sudo apt update # again rquire to update
sudo apt install fontconfig openjdk-17-jre  # install the java
java -version 
```
- install jenkins 
```git
visit the link  - https://www.jenkins.io/doc/book/installing/linux/#debianubuntu.
Execute the command one by one. dont try to run the command in one short.

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key

echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt-get update

sudo apt-get install jenkins
```

- start jenkins
```git
sudo systemctl enable jenkins # You can enable the Jenkins service to start at boot with the command
sudo systemctl start jenkins  #You can start the Jenkins service with the command
sudo systemctl status jenkins  # You can check the status of the Jenkins service using the command
```

# basic configuration 
- open it in browser by the ip with port no 8080
- unlock the jenking as the step
- installed jenkins plugin
- create  your 1st admin user
- jenkins is ready and click there to enter to dashboard

# Next create new pipeline  as per your projet requirement 




