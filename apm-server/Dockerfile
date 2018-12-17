FROM docker.elastic.co/apm/apm-server:6.5.3
COPY apm-server.yml /usr/share/apm-server/
USER root
RUN chown root:apm-server /usr/share/apm-server/apm-server.yml
WORKDIR /usr/share/apm-server

USER 1000
ENV PATH=/usr/share/apm-server:$PATH



