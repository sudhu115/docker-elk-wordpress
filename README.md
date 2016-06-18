#  Docker compose based ELK setup

# Project Description

  Blogging application in Wordpress is deployed on the AWS
  cloud. The application and the computer where application is running
  is continuously monitored. For monitorting centralised logging 
  and dashboarding is implemented using the ELK (ElasticSearch, Logstash, Kibana) 
  stack. The entire infrastructure is a container based system.  

# Goals

  1. We will use Ansible for provisioning the minimal AWS infrastructure to
     run the ELK based logging infrastructure.

  2. We will create a Docker compose based ELK setup, so that it's repeatable
     and demonstrable on a development machine.
  
  3. Then we will deploy dockerized WordPress application.

  4. Then we will setup monitorting of application, AWS resources via ELK.

  5. We will prepare an insightful dashboard to visualize logs.

  
# Specifications

  - OS: Ubuntu Server 14.04 64-bit
  - App Server: Gunicorn/Nginx
  - Python: 2.7
  - Ansible
  - Docker 1.10
  - Wordpress official Docker image (https://hub.docker.com/_/wordpress/)
  - ElasticSearch
  - Logstash
  - Kibana

# Further reading

  For understanding the setup steps and documentation related to the project, please refer
  https://github.com/ayogi/docker-elk-wordpress/blob/master/docs/document.org

