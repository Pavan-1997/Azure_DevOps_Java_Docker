# Azure DevOps Pipeline setup having tasks Maven-Push DockerHub and containerized the Java application

In this project I have set up a Azure pipeline where the source code is fetched from Azure Repos, Pipeline was set up having tasks for Maven, Push Artifact, and Push Image to DockerHub where finally the application is docker containerized

The pipeline is executed on an agent where I have made use of an EC2 Ubuntu machine to run the jobs.

In the end ran the docker container in the Bash Script as a task in the pipeline and later accessed the application.

All the commands are documented in the CMD.txt file

![image](https://github.com/Pavan-1997/Azure_DevOps_Java_Docker/assets/32020205/7dbf30cb-435c-4e85-bb19-b050b1fa2de8)

![image](https://github.com/Pavan-1997/Azure_DevOps_Java_Docker/assets/32020205/95b69e88-f8fc-4eb0-8548-cdaefa9e4727)
