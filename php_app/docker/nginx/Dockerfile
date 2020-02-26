FROM nginx:latest

RUN /bin/bash -c 'mv /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/backup.default.conf'

ADD ./conf/default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80