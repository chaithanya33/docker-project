# PROJECT STRUCTURE

<img width="800" height="320" alt="Untitled Diagram drawio" src="https://github.com/user-attachments/assets/afdeabf1-25c7-4ae3-9130-d8196aead609" />









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
3)docker pipeline 
4) sonarqube
5)trivy docker image
6)synk tool /to store artifacts and suecrity tool scan 
and integrate plugins in jenkins in plugins and systems

overall i added some security checks and post build actions if it passes security checks and warnings should be ignored checks then only it pushes into docker images

stages

<img width="1816" height="755" alt="Screenshot 2025-11-26 131910" src="https://github.com/user-attachments/assets/e0d9cbbc-82e6-404c-b06e-bade9f8f996a" />


# final output

<img width="1767" height="898" alt="Screenshot 2025-11-26 131758" src="https://github.com/user-attachments/assets/d22457b3-c159-4fe9-a451-61aff5861c9d" />

<img width="1913" height="764" alt="Screenshot 2025-11-26 131931" src="https://github.com/user-attachments/assets/42602e50-a13a-4ee8-afd4-0992949cf32f" />

<img width="1896" height="1008" alt="Screenshot 2025-11-26 132323" src="https://github.com/user-attachments/assets/d96d1b8e-b31a-437e-8060-5a172076da90" />

<img width="1884" height="993" alt="Screenshot 2025-11-26 132340" src="https://github.com/user-attachments/assets/fdf31bdd-7c85-4990-8f7e-932668588bf8" />























