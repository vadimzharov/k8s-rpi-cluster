FROM alpine:latest
RUN apk --no-cache add minidlna
ENTRYPOINT ["minidlnad", "-f", "/etc/minidlna/minidlna.conf", "-S"]
