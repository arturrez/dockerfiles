FROM alpine:latest
RUN apk add --update netcat-openbsd && rm -rf /var/cache/apk/*
ADD start.sh /
RUN chmod +x /start.sh
EXPOSE 8080
CMD "/start.sh"
