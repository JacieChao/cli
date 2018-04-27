FROM ubuntu:16.04
# FROM arm=armhf/ubuntu:16.04 arm64=arm64v8/ubuntu:16.04
RUN apt-get update && apt-get install -y ca-certificates openssh-client
COPY rancher /usr/bin/
WORKDIR /mnt
ENTRYPOINT ["rancher"]
CMD  ["--help"]