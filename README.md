# PROJECT STRUCTURE


<img width="1053" height="645" alt="image" src="https://github.com/user-attachments/assets/a0e926d0-2c30-4d7e-b6db-526d33727516" />





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




