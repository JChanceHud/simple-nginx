FROM alpine:latest
MAINTAINER Chance Hudson

RUN apk add --no-cache nginx && \
  mkdir -p /run/nginx && \
  mkdir /www

WORKDIR /www

COPY nginx.conf /etc/nginx/nginx.conf

CMD ["nginx", "-g", "daemon off;"]
