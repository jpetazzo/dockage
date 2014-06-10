FROM debian:jessie
RUN apt-get -q update
RUN apt-get -qy install build-essential
RUN apt-get -qy install curl
RUN curl https://www.kernel.org/pub/linux/utils/util-linux/v2.24/util-linux-2.24.tar.gz \
    | tar -zxf-
WORKDIR /util-linux-2.24
RUN ./configure --without-ncurses
RUN make nsenter
CMD cp nsenter /nsenter
