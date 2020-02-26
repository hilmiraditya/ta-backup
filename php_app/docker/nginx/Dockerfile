FROM nginx:latest

RUN /bin/bash -c 'mv /etc/nginx/nginx.conf /etc/nginx/backup.old.conf'

ADD ./conf/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80