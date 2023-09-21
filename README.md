# Jenkins
Jenkins deployment process  
- sudo apt update
# command to install java8
- sudo apt update openjdk-8-jdk
# Adding jenkins repository 
# a. Import GPG keys
- wget -q -O -https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
# b. add the jenkins repository to the system
- sudo sh -c 'echo deb http://pkg.jenkins.io./debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
# steps to install jenkins
- sudo apt update
- sudo apt install jenkins
- sudo systemctl status jenkins
# modify firewall to allow jenkins
- sudo ufw allow 8080
- sudo ufw status
- sudo ufw enable
# setup jenkins
- ip address : 8080


