# Deploying Multi-Container Microservices in AKS
![image](https://user-images.githubusercontent.com/13543372/236958430-a1e3116d-fca8-4742-8080-91e03709e77b.png)  
# Devops Pipeline  
![image](https://github.com/felipesalvadordev/run-devops/assets/13543372/9d3ecfca-d646-43be-9c37-c76dc7c07efe)  
# Deploy to Azure Kubernetes Services (AKS) through CI/CD Azure Pipelines  
![image](https://github.com/felipesalvadordev/run-devops/assets/13543372/c64e54e3-4247-4d46-b05b-fc2eba9cda99)  

# Shopping MVC Client Application
First of all, we are going to develop Shopping MVC Client Application For Consuming Api Resource which will be the Shopping.Client Asp.Net MVC Web Project. But we will start with developing this project as a standalone Web application which includes own data inside it. And we will add container support with DockerFile, push docker images to Docker hub and see the deployment options like “Azure Web App for Container” resources for 1 web application.

# Shopping API Application
After that we are going to develop Shopping.API Microservice with MongoDb and Compose All Docker Containers. This API project will have Products data and performs CRUD operations with exposing api methods for consuming from Shopping Client project. We will containerize API application with creating dockerfile and push images to Azure Container Registry.

# Mongo Db
Our API project will manage product records stored in a no-sql mongodb database as described in the picture. we will pull mongodb docker image from docker hub and create connection with our API project. At the end of the section, we will have 3 microservices whichs are Shopping.Client — Shopping.API — MongoDb microservices. As you can see that, we have

Created docker images, Compose docker containers and tested them, Deploy these docker container images on local Kubernetes clusters, Push our image to ACR, Shifting deployment to the cloud Azure Kubernetes Services (AKS), Update microservices with zero-downtime deployments.



References:  
https://medium.com/aspnetrun/preparing-multi-container-microservices-applications-for-deployment-793d60f48d31  
https://github.com/aspnetrun/run-devops

