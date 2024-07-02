FROM nginx:latest
COPY nginx.conf /etc/nginx/nginx.conf
RUN apt update && \
    apt install vim -y
RUN mkdir -p /var/logs/nginx
EXPOSE 80