FROM ubuntu

LABEL version="2.0" \
      description="For docker study"

RUN apt update && \
    apt install nginx apt-utils -y && \
    echo "\ndaemon off;" >> "/etc/nginx/nginx.conf" && \
    echo "<h1>hello Dockerfile</h1>" >> /usr/share/nginx/html/index.html

ENTRYPOINT ["nginx"]

EXPOSE 80

