# docker-kafka-elk

This project contains the docker configuration needed to lunch kafka, zookeeper, logstash, elasticsearch and kibana with docker-compose.

1 - Run Kafka and zookeeper
```dockerfile 
docker-compose -f docker-compose-kafka.yml up -d
```
2 - Run logstash, elasticsearch and kibana
```dockerfile 
docker-compose -f docker-compose-elk.yml up -d --build
```
Don't forget to update configuration files with your own's.