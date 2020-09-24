1) Created a Springboot project(Simple REST API) in IntelliJ using Spring Starter IO 
2) Added docker file
3) Build Image
4) Run

# docker-spring-boot
  501  docker -v
  502  pwd
  503  docker build -f Dockerfile -t docker-spring-boot .
  504  docker images
  505  docker run -p 8085:8085 docker-spring-boot
  511  history
  512  ls
  511  git init 
  513  git status
  514  git add .
  515  git commit -m "initial checkin"
  516  git status
  517  git remote add origin https://github.com/pankajtech2020/docker-spring-boot.git
  518  git status
  519  git push -u origin master
  520  git status
