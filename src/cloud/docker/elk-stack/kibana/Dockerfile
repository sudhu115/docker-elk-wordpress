FROM kibana:latest
COPY config/kibana.yml /opt/kibana/config/
ENV http_proxy "http://10.4.20.103:8080"
ENV https_proxy "http://10.4.20.103:8080"
RUN apt-get -y update && apt-get install -y vim
