FROM ubuntu:jammy

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && apt upgrade -y
RUN apt install gnome -y

RUN wget https://github.com/kasmtech/KasmVNC/releases/download/v0.9.3-beta/kasmvncserver_jammy_0.9.3_amd64.deb
RUN apt install ./kasmvncserver_*.deb
