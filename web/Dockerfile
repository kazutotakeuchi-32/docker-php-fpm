FROM nginx:latest

RUN apt update && apt install -y procps && apt install -y sudo && apt install -y vim
COPY settings/default.conf /etc/nginx/conf.d/default.conf
