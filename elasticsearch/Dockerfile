FROM docker.elastic.co/elasticsearch/elasticsearch:7.15.2

COPY ./config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

# Install kuromoji plugin
RUN elasticsearch-plugin  install analysis-kuromoji