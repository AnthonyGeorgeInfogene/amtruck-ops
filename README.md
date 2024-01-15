# Kafka Cluster Composition

## Provectus
https://docs.kafka-ui.provectus.io/overview/readme

## KRaft mode
https://docs.confluent.io/platform/current/kafka-metadata/config-kraft.html

## Topics creation
`docker ps`

`docker exec -it broker bash`

`kafka-topics --bootstrap-server localhost:9092 --topic <topic_name> --create --partitions 3 --replication-factor 1`