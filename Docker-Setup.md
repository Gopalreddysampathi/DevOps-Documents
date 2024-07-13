
# Docker Setup (Amazon Linux / Ubuntu)




## Setup Linux VM (Amazon Linux / Ubuntu)

1.Login into AWS Cloud account

2.Create Linux VM and connect to it using MobaXterm
## Install Docker In Amazon Linux VM


```bash
sudo yum update -y 
sudo yum install docker -y
sudo service docker start
sudo usermod -aG docker ec2-user
exit
```

## Install Docker In Ubuntu VM


```bash
sudo apt update
curl -fsSL get.docker.com | /bin/bash
sudo usermod -aG docker ubuntu 
exit
```

## Verify docker installation


```bash
docker -v
```
    