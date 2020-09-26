1) Created a Springboot project(Simple REST API) in IntelliJ using Spring Starter IO 
2) Added docker file
3) Build Image
4) Run

# docker-spring-boot
  1) docker -v
  2) pwd
  3) docker build -f Dockerfile -t docker-spring-boot .
  4) docker images
  5) docker run -p 8085:8085 docker-spring-boot
  6) history
  7) ls
  8) git init 
  9) git status
  10) git add .
  11) git commit -m "initial checkin"
  12) git status
  13) git remote add origin https://github.com/pankajtech2020/docker-spring-boot.git
  14) git status
  15) git push -u origin master
  16) git status
----------------------
17) To override local changes- 
git reset --hard origin/master

18) when we are trying to push to remote repository but has created a new file on remote which has not been pulled yet, let say Readme. In that case as the error says
git rejects the update

as we have not taken updated remote in our local environment. So Take pull first from remote

git pull
It will update your local repository and add a new Readme file. Then Push updated changes to remote

git push origin master