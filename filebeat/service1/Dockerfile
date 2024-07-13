FROM elastic/filebeat:8.14.3

COPY filebeat.yml /usr/share/filebeat/filebeat.yml

USER root
RUN chmod go-w /usr/share/filebeat/filebeat.yml

USER filebeat
