# kafka-producers
Sample Kafka Producers

## Building and Running

```
./gradlew shadowJar
java -jar build/libs/kafka-producer-application-standalone-0.0.1.jar configuration/dev.properties input.txt
```

### Further Reading
- https://kafka-tutorials.confluent.io/creating-first-apache-kafka-producer-application/kafka.html