
# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:7.6.2

RUN logstash-plugin install logstash-output-lumberjack

USER root

RUN mkdir /usr/share/logstash/keys
RUN chown -R root /usr/share/logstash/
RUN chmod -R go-w /usr/share/logstash/

COPY TrustExternalCARoot.crt /usr/share/logstash/keys
