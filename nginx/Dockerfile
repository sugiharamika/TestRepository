FROM nginx

ADD app /app
ADD proxy.conf /etc/nginx/conf.d/
ADD logsetting.conf /etc/nginx/conf.d/

CMD nginx -g "daemon off;"

EXPOSE 80

