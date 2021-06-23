FROM nginx:1.19.4

CMD ["nginx"]

# Work Directory
WORKDIR /var/www/app

COPY ./docker/services/nginx/conf.d/default.conf  /etc/nginx/conf.d
COPY ./docker/services/nginx/nginx.conf /etc/nginx/nginx.conf
COPY ./docker/services/nginx/sites/default.conf /etc/nginx/sites-available/default.conf

EXPOSE 80 443