FROM debian:jessie
RUN apt-get -q update
RUN apt-get -qy install wpasupplicant
CMD ["wpa_supplicant", "-d", "-iwlan0", "-c/wpa_supplicant.conf" ]
