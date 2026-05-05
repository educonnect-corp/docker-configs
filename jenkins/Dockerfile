  # Jenkins CI — EduConnect DevOps                                                                                                                           
  # Port 8080 — réseau LAN interne (172.21.0.20)
  FROM jenkins/jenkins:2.426.1-lts                                                                                                                           
                                                                                                                                                             
  USER root                                                                                                                                                  
  RUN apt-get update && apt-get install -y curl mongodb-clients                                                                                              
  USER jenkins
