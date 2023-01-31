# Authenticate Github actions with DockerHub using AccessTokens

## **Prerequisite**

1. Create an account in github and create a new repository
2. Create an account in dockerhub

## **Generate access token in DockerHub**

1. DockerHub > Settings > Security > Access Tokens > New Access Token
2. Give a description eg. give the repository name created to easily identify
3. Click Create and leave the page like that we need to use this token in github. 

Add the DockerHub username and access Token in Github repository

1. In github repository > settings > secrets and variables > actions > New repository secrets
2. Name >  enter a name, eg: DockerHub_User
3. In value > enter username used to login to DockerHub
4. Add Secret
5. Click New repository secrets
6. Add a new secret name, eg: DockerHub_Token
7. In value > copy and paste the dockerHub token. 
8. Add Secret 

