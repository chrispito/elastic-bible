# elastic-bible

You can now build it by running:

> <code> docker build -t elastic-bible .</code>

> <code> docker run --rm -p 9200:9200 elastic-bible</code>

## By default, the stack exposes the following ports:

1. 5000: Logstash TCP input.
2. 9200: Elasticsearch HTTP
3. 9300: Elasticsearch TCP transport
4. 5601: Kibana