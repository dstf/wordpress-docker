FROM nginx:1.21.0 


RUN apt update && apt install openssl 



RUN rm /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/

COPY sel-ssl.sh /
RUN chmod +x /sel-ssl.sh && /sel-ssl.sh

WORKDIR /var/www/html
