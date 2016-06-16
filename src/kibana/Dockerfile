ROM kibana:latest

RUN apt-get update && apt-get install -y netcat

COPY start.sh /tmp/start.sh
RUN chmod +x /tmp/start.sh

RUN kibana plugin --install elastic/sense

CMD ["/tmp/start.sh"]
