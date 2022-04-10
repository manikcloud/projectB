wget -q -O - https://jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add - 
sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian binary/ > /etc/apt/sources.list.d/jenkins.list' 
sudo apt-get install jenkins 
sudo service jenkins status 
sudo systemctl start jenkins
sudo systemctl status jenkins
