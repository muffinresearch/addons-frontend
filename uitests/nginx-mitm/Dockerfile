FROM nginx
EXPOSE 80

ADD fake-certs/nginx-mitm.crt /etc/nginx/ssl/nginx-mitm.crt
ADD fake-certs/nginx-mitm.key /etc/nginx/ssl/nginx-mitm.key
ADD nginx-mitm.conf /etc/nginx/conf.d/nginx-mitm.conf
