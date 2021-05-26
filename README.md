# Kafka Producers

Sample Kafka Producers

## Startup

```
docker-compose up
```

## Building

```
./gradlew shadowJar
```

## Running

```
java -jar build/libs/kafka-producer-application-standalone-0.0.1.jar configuration/dev.properties input.txt
```

### Further Reading
- https://kafka-tutorials.confluent.io/creating-first-apache-kafka-producer-application/kafka.html
- https://kafka-tutorials.confluent.io/kafka-producer-callback-application/kafka.html