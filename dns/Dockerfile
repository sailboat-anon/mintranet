FROM prehley/rpi-bind9:latest
COPY etc/bind/* /etc/bind/
COPY var/lib/bind/* /var/lib/bind/
COPY var/log/bind/* /var/log/bind/
COPY etc/bind/zones/* /etc/bind/zones/
RUN ["named", "-g", "-p", "53"]
