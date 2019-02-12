FROM nginx:latest
#RUN apt-get update && apt-get upgrade -y && apt-get install curl wget tree vim -y

COPY ./config/nginx.conf /etc/nginx/nginx.conf
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]