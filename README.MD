### Docke file 
Docker file of declrative way of creating our onw iImages 
Docker will give us simple syntex to create our own Images


File Name should be "Dockerfile"


#### Push our code to Git hub
Go to Terminal -> GIT BASH in VS code
Cd Dockerfile\
git init
git add .
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/pativadan/Dockerfiles.git
git push -u origin master

;;;;;;;;;;;;;;;;;
### from putty 

 git clone  https://github.com/pativadan/Dockerfiles.git
 cd Dockerfiles
 cd FROM
 docker login 
 user name 
 and password 

;;;;;;

### How to buld Images from Dockerfile
docker build -t [docker-hub-url]/[user-name]/[image-name]:version .
Ex: docker build -t docker.io/pativadan/from:v1 .
### push the image to Docker hub
docker push [docker-hub-url]/[user-name]/[image-name]:version
Ex: docker push -t docker.io/pativadan/from:v1 