# Elasticsearch
#
# VERSION               1.4.4

FROM dockerfile/java:oracle-java7
MAINTAINER Martin Sturm
DESCRIPTION Elasticsearch 1.3.1 on latest ubuntu container

RUN wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.4.4.tar.gz

RUN tar -xf elasticsearch-1.4.4.tar.gz
RUN rm elasticsearch-1.4.4.tar.gz
RUN mv elasticsearch-1.4.4 /opt/elasticsearch

EXPOSE 9200 9300

CMD /opt/elasticsearch/bin/elasticsearch
