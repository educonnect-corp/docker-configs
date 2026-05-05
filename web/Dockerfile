  # EduConnect Web — PHP 7.4 Apache
  # TODO: migrer vers PHP 8.2 (ticket #234 — en cours)                                                                                                       
  FROM php:7.4-apache                                                                                                                                        
                                                                                                                                                             
  RUN apt-get update && apt-get install -y \                                                                                                                 
      libpdo-mysql \                                        
      && docker-php-ext-install pdo_mysql                                                                                                                    
                                                                                                                                                             
  COPY . /var/www/html/
