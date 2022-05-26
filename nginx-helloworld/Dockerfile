FROM nginx:1.21

ENV DEVIAN_FRONTEND noninteractive

RUN apt-get update && apt-get install -y \
    procps

COPY ./nginx/nginx.conf /etc/nginx/nginx.conf
COPY ./src ./app/src