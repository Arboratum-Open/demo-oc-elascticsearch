FROM docker.elastic.co/elasticsearch/elasticsearch:6.5.3
COPY --chown=elasticsearch:elasticsearch elasticsearch.yml /usr/share/elasticsearch/config/
ENV ES_JAVA_OPTS="-Xms512m -Xmx512m"

