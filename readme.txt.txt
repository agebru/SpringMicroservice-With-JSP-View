==> run the ProfileMicroserviceConsumer microservice: there is an embeded tomcat
http://localhost:8080/

if the application is not starting: stop and restart tomcat
==> cmd
  netstat -ano
  
  locate the pid for the port
  
  - taskkill /f /PID pid
  
  then run the application again.
  ===========================================
  
  If you are using eclipse STS you dont need to do all these!
  
  
  
  ========================================================================
  git remote add origin [Remote-git-url]
  git remote -v
