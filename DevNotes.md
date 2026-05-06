# Kafka
## To get all events in a topic
> /opt/kafka/bin/kafka-console-consumer.sh \
  --bootstrap-server broker:9092 \
  --topic order_status \
  --from-beginning

# To do
- [x] healthcheck
- [-] depends_on is not ready
- [x] env variables
CI/CD :
- [ ] Build Docker images
- [ ] Run linting
- [ ] Run unit tests
- [ ] Spin up your stack with docker compose (?)
- [ ] Run smoke tests (API calls, Kafka connectivity, etc.)
- [ ] Persistency in Cloud
Add integration tests for Kafka
Use .env + secrets management if aiming cloud
Image versioning + registry
Lint & validate the Docker setup
Add “wait-for-it” / readiness logic in tests
