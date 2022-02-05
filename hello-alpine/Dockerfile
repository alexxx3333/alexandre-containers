FROM alpine:3.15.0
LABEL version="3.15.0" maintainer="alexandre" os="linux" distro="alpine"

ENV CONTAINER_USER = "sertain"
RUN useradd $CONTAINER_USER --disabled-password && mkdir "/home/aguirre/"
CMD echo "hello-alpine, I’m $CONTAINER_USER and this is a container from my first image"
