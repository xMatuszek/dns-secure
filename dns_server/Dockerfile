FROM ubuntu:latest

RUN apt update
RUN apt install -y nano
RUN apt install bind9 -y
RUN apt-get install -y bind9 dnsutils

EXPOSE 53/tcp
EXPOSE 53/udp

CMD ["/usr/sbin/named", "-f"]