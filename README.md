#  Docker compose based ELK setup.

# Project Description
  A blogging application in Wordpress is to be deployed on the AWS
  cloud. The application and the computer where application is running
  is to be continuously monitored. Centralised logging and dashboarding 
  is to be implemented using the ELK (ElasticSearch, Logstash, Kibana) 
  stack. The entire infrastructure is intended to be a container based 
  system.  

# Requirements

  1. Create a Docker compose based ELK setup, so that it's repeatable
     and demonstrable on a development machine.
  2. Use Ansible for provisioning the minimal AWS infrastructure to
     run the ELK based logging infrastructure.
  3. Deploy dockerized WordPress based blogging application.
  4. Monitor the AWS resources and the blogging application using you
     ELK based centralised logging and monitoring infrastructure.
  5. Demonstrate your knowledge and understanding by preparing an
     insightful dashboard of your choice.

  Use the official WordPress Docker image to run a web application and
  monitor it using the centralised logging setup that is built above.

# Specifications
  - OS: Ubuntu Server 14.04 64-bit
  - App Server: Gunicorn/Nginx
  - Python: 2.7
  - Ansible
  - Docker 1.10
  - Wordpress official Docker image
    https://hub.docker.com/_/wordpress/
  - ElasticSearch
  - Logstash
  - Kibana

