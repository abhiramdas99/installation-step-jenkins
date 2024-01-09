# installation-step-jenkins

Guys sometime we get lot of  eroro during jenkins installation
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
