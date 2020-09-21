how to start container 
docker container run --name jenkins-dev -d -p 8083:8080 jenkins/jenkins 
docker conatiner rm $(docker container ls -a)
docker container stop containerid/name
