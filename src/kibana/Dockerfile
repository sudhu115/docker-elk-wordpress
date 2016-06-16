FROM kibana:latest

ENV http_proxy "http://proxy.iiit.ac.in:8080"
ENV https_proxy "http://proxy.iii.ac.in:8080"
RUN apt-get update && apt-get install -y netcat

COPY start.sh /tmp/start.sh
RUN chmod +x /tmp/start.sh

RUN kibana plugin --install elastic/sense

CMD ["/tmp/start.sh"]
