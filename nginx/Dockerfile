FROM nginx:stable-alpine

COPY config/proxy.conf /etc/nginx/conf.d/default.conf
COPY config/err.conf /etc/nginx/conf.d/err.conf

COPY www /usr/share/nginx/html
