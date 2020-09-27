# how to start container 

docker container run --name jenkins-dev -d -p 8083:8080 jenkins/jenkins 

docker conatiner rm $(docker container ls -a)

docker container stop containerid/name

docker exec jenkins-dev cat /var/jenkins_home/secrets/initialAdminPassword

docker image rm cd14cecfdb3a

C:\Users\Anubhav>docker exec jenkins-dev cat /var/jenkins_home/secrets/initialAdminPassword  

e6b1172aab7f43e1b864a8f170a9cd0f                                                                                                                                                                                                                                                                                                                C:\Users\Anubhav>docker exec -it jenkins-dev bash 

jenkins@9d91f4964bea:/$ cd /var/jenkins_home/secrets/initialAdminPassword

bash: cd: /var/jenkins_home/secrets/initialAdminPassword: Not a directory

jenkins@9d91f4964bea:/$ cd /var/jenkins_home/secrets

jenkins@9d91f4964bea:~/secrets$ cat initialAdminPassword 

e6b1172aab7f43e1b864a8f170a9cd0f  

jenkins@9d91f4964bea:~/secrets$ exit   

docker exec -it jenkins-dev bash

cd ~/.ssh/

 ls -lrth
 
 
 
 docker tag kingfirstui:1.0 sushil077/kingfirstui:1.0
 
 docker push sushil077/kingfirstui:1.0
 
 docker container run -it -p 8087:80 --name=angular-nginx-ui kingfirstui:1.0 
 
 
 
 
 
  ssh-keygen -t rsa
