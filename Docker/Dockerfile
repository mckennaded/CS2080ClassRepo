FROM ubuntu

#RUN mkdir /bin
COPY assignment.sh /bin
RUN chmod +x assignment.sh
RUN chmod +rwx -R /bin

RUN /bin/assignment.txt
RUN apt update
RUN apt install nginx

RUN service nginx start
