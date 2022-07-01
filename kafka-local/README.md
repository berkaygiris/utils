# Kafka Local

This compose file enables running:
- A zookeeper instance in 2181 port
- A kafka broker in 9092 port
- A management ui in 8085 port



## Reference
Took it from [provectus/kafka-ui](https://github.com/provectus/kafka-ui/blob/master/documentation/compose/kafka-ui.yaml) and made it lighter.

The original compose file has following extensions if you need moar:
- Connect
- Schema Registry
- Init topics
- Multiple kafka brokers/zookeepers
