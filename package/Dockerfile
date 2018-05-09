FROM alpine:3.5
# FROM arm=armhf/alpine:3.5 arm64=arm64v8/alpine:3.5
RUN apk add --no-cache ca-certificates openssh-client
COPY rancher /usr/bin/
WORKDIR /mnt
ENTRYPOINT ["rancher"]
CMD  ["--help"]