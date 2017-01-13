FROM alpine:3.5

RUN apk update && apk add \
        lftp \
    && rm -rf /var/cache/apk/* && rm -rf /tmp/*

CMD ["/bin/sh"]
