FROM nginx:alpine

RUN rm ./etc/nginx/conf.d/default.conf

RUN mkdir -p /var/www/certbot

COPY ./nginx.conf /etc/nginx/conf.d/default.conf