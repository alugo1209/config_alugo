FROM nginx:stable

ENV TZ=America/Bogota
ADD ./nginx.conf /etc/nginx/nginx.conf

EXPOSE 8085

CMD ["nginx", "-g", "daemon off;"]
