FROM docker.elastic.co/elasticsearch/elasticsearch:6.5.3
COPY elasticsearch.yml /usr/share/elasticsearch/config/
RUN chown elasticsearch:elasticsearch /usr/share/elasticsearch/config/elasticsearch.yml
ENV ES_JAVA_OPTS="-Xms512m -Xmx512m"

