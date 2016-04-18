This is our Docker image for ElasticSearch in development and production. It is runs an ElasticSearch `2.3.1` node.

It assumes that you will standup containers with the following environment:

 - Configuration is mounted at `/usr/share/elasticsearch/config`

You can persist the index by mounting `/usr/share/elasticsearch/data` in the host.
