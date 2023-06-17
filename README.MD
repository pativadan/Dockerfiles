### Docke file 
Docker file of declrative way of creating our onw iImages 
Docker will give us simple syntex to create our own Images

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


File Name should be "Dockerfile"

### How to buld Images from Dockerfile
docker build -t [docker-hub-url]/[user-name]/[image-name]:version   