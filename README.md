# almserver 

Application Lifecycle Management Server configuration and DevOps tools

Running:
docker-compose up -d

it will create a suite composed by Gogs, Jenkins, Nexus3 and Sonarqube



# Using Gogs

**Create a new repository on the command line**

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin http://<dockerhost>:10080/alm/almserver.git
git push -u origin master


**Push an existing repository from the command line**

git remote add origin http://<dockerhost>:10080/alm/almserver.git
git push -u origin master
