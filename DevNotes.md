# Kafka
## To get all events in a topic
> /opt/kafka/bin/kafka-console-consumer.sh \
  --bootstrap-server broker:9092 \
  --topic order_status \
  --from-beginning

# To do
- [x] healthcheck
- [ ] depends_on is not ready
- [ ] env variables
- [ ] Persitency in Cloud