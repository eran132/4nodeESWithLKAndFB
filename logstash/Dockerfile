ARG ELK_VERSION

FROM logstash:${ELK_VERSION}

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
COPY pipeline/ /usr/share/logstash/pipeline/