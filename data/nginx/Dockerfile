FROM nginx

COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/conf.d/default.conf
RUN apt-get update
RUN apt-get install -y vim
