# PROJECT STRUCTURE








Launch EC2 server with 20 GB volume and in free tier instance type should be m7i-flex.large

overall tools and dependencies
1)java
2)git
3)jenkins
4)docker (1)trivy tool install through docker image ) //2)default path  mv trivy /usr/local /bin and u should edit it //3) vi .bashrc // export PATH =$PATH:/usr/local/bin/
#make it souurce 
4)source .bashrc //then it works

plugins in jenkins  
1)node.js
2)eclips Temurin installer 
3) OWASP dependency 4)docker pipeline 
5) sonarqube
and integrate plugins in jenkins in plugins and systems

overall i added some security checks and post build actions if it passes security checks and warnings should be ignored checks then only it pushes into docker images




<img width="1850" height="1015" alt="Screenshot 2025-11-22 112528" src="https://github.com/user-attachments/assets/91888c7b-ff8a-4089-a796-0f4d75c0d73a" />




