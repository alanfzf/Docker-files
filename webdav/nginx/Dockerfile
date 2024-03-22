FROM nginx:latest

COPY certificate.crt /etc/nginx/ssl/nginx-selfsigned.crt
COPY private.key /etc/nginx/ssl/nginx-selfsigned.key

COPY nginx.conf /etc/nginx/nginx.conf
