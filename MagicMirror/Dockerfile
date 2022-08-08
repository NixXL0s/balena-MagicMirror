FROM bastilimbach/docker-magicmirror:latest

COPY ./config /opt/magic_mirror/config
COPY ./modules /opt/magic_mirror/modules

COPY moduleInstall.sh /opt/moduleInstall.sh

#RUN ./opt/moduleInstall.sh
RUN apt-get update
