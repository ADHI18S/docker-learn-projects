# syntax=docker/dockerfile:1
ARG version=alphine
FROM nginx:${version}

WORKDIR /usr/share/nginx/html

copy ./files /usr/share/nginx/html

EXPOSE 80/tcp

ENTRYPOINT ["nginx","-g","daemon off"]

