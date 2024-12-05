FROM ubuntu

RUN apt-get update && \
    apt-get install -y vim nginx && \
    apt-get clean

COPY assign7.sh /usr/local/bin/assign7.sh

RUN chmod +x /usr/local/bin/assign7.sh

CMD ["/usr/local/bin/assign7.sh"]


