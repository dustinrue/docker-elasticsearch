# Setup

Install docker. If on Mac or Windows ensure you've configured at least 6GB of memory allowed for docker instances. Run `docker-compose up -d` to get everything running. -d will put it in the background and the services are configured to start on docker start. Each Elasticsearch node is configured for 1GB of heap memory. 

You will find Elasticsearch available at [http://localhost:9200](http://localhost:9200), Cerebro at [http://localhost:9000](http://localhost:9000) and Kibana at [http://localhost:5601](http://localhost:5601).