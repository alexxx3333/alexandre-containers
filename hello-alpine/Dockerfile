FROM alpine:3.15.0
LABEL version="1.0.0" maintainer="alexandre" os="linux" distro="alpine"
ENV CONTAINER_USER = "alexxx333"
RUN useradd -S $CONTAINER_USER --disabled-password && mkdir "/home/aguirre/"
CMD echo "hello-alpine, I’m $CONTAINER_USER and this is a container from my first image"
