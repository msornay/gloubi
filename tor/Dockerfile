FROM alpine:latest

RUN apk update && apk add tor && rm -rf /var/cache/apk/*

COPY torrc /etc/tor/torrc

USER tor
ENTRYPOINT tor
