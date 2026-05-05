  # EduConnect — Docker Configs
                                                                                                                                                             
  Configurations Docker pour l'infrastructure EduConnect Corp.
                                                                                                                                                             
  ## Services                                               
  - web/ : Portail étudiant PHP (172.20.0.10:80)
  - mail/ : Serveur mail Postfix + webmail (172.20.0.20)                                                                                                     
  - jenkins/ : CI/CD Jenkins (172.21.0.20:8080)                                                                                                              
  - db : MongoDB 7.0 + Redis (172.23.0.10)                                                                                                                   
                                                                                                                                                             
  ## Réseau                                                                                                                                                  
  Voir infra-ansible/inventory/hosts.yml pour la topologie complète.
