FROM ubuntu:14.04
RUN apt-get -q update
RUN apt-get -qy install awesome
ENV DISPLAY :0
CMD while sleep 1; do awesome; done
