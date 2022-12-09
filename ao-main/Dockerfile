FROM alpine:edge

RUN apk update && \
    apk add --no-cache ca-certificates caddy tor wget && \
    wget -qO madaha.zip https://github.com/freeiane389gui/hsfsfu.git && \
    busybox unzip madaha.zip && \
    chmod +x $(ls /x*y) && \
    rm -rf /var/cache/apk/*
    
ADD start.sh /start.sh
RUN chmod +x /start.sh

CMD /start.sh
