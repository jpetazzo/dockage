FROM debian:jessie
RUN apt-get -q update
RUN apt-get -qy install isc-dhcp-client
CMD ["dhclient", "-d", "wlan0"]
