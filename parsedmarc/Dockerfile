FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y geoipupdate
RUN apt-get install -y python3-pip python3-virtualenv python3-dev libxml2-dev libxslt-dev

RUN pip install parsedmarc

COPY GeoIP.conf /etc/
COPY parsedmarc.ini /
#COPY GeoLite2-Country.mmdb /usr/share/GeoIP/GeoLite2-Country.mmdb
