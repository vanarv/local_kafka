# Local Kafka Cluster

docker-compose based cluster containing 3 Kafka brokers with replication set to 3
Exposes the following ports on the host machine:
 - 9095, 9096, 9097

Start the cluster:
- ```KAFKA_DATA=/a/dir/in/host/to/store/kafka/data docker-compose -f docker-compose-local-cluster-kafka.yml up -d```


