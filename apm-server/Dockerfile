FROM docker.elastic.co/apm/apm-server:6.5.3
COPY apm-server.yml /usr/share/apm-server/
USER root
RUN chown -R root:root /usr/share/apm-server
WORKDIR /usr/share/apm-server

ENV PATH=/usr/share/apm-server:$PATH



