## Workspace components

This Workspace contains the three components of the Elastic Stack: the Elasticsearch data store, 
the data flow engine Logstash and the Kibana as presentation layer. For more information, coming directly 
from the developers: https://www.elastic.co/webinars/introduction-elk-stack.

### Elasticsearch
Elasticsearch is a distributed, RESTful search and analytics engine. As the heart of the Elastic Stack, 
it centrally stores your data so you can discover the expected and uncover the unexpected.

This is a very small bundle deployment, that is why the Elasticsearch is only configured to use 1GiB of 
memory. 

### Logstash
Logstash is an open source, server-side data processing pipeline that ingests data from a multitude of 
sources simultaneously, transforms it, and then sends it to your favorite “stash.” In this case we stash 
all the incoming data in Elasticsearch.

### Kibana
Kibana lets you visualize your Elasticsearch data and navigate the Elastic Stack.
