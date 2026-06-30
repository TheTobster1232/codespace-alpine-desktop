FROM alpine:latest

RUN apk update && apk add --no-cache \
    alpine-desktop \
    xfce4 \
    x11vnc \
    xvfb \
    novnc \
    websockify \
    firefox-esr \
    bash

RUN mkdir -p /root/.vnc && \
    x11vnc -storepasswd 1234 /root/.vnc/passwd
