FROM docker:dind
RUN ls
EXPOSE 2376
VOLUME /var/run/docker.sock /var/run/docker.sock
RUN docker pull maven:3.8.1-adoptopenjdk-11