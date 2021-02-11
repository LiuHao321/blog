---
title: "Jenkins"
date: 2021-02-10T15:14:56+08:00
draft: true
---
以root用户进入容器
`docker exec -it -u root <container id> bash`  
7.启动jenkins  
`docker run -d -p 9090:8080 --name jenkins -e TZ="Asia/Shanghai" -v /home/jenkins:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock  -v $(which docker):$(which docker)  jenkinszh/jenkins-zh:lts`  