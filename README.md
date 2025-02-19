//Software Installation steps
//install docker
1) sudo apt update
2) sudo apt install docker.io -y
3) docker info

//Install docker-compose 
1)sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
2)sudo chmod +x /usr/local/bin/docker-compose
3)docker-compose --version

//Install java
1) sudo apt update
2) sudo apt install fontconfig openjdk-17-jre
3) java -version

//Install Jenkins
1)sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian/jenkins.io-2023.key
2)echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \
  https://pkg.jenkins.io/debian binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
3)sudo apt-get update
4)sudo apt-get install jenkins

//Install Ansible
https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-22-04


