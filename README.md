
```
./gradlew run

# run from the hello world


# application output stream
kafka-console-consumer --bootstrap-server localhost:9092 --topic total_purchases --from-beginning --property print.key=true --property value.deserializer=org.apache.kafka.common.serialization.IntegerDeserializer

# input stream 
kafka-console-consumer --bootstrap-server localhost:9092 --topic inventory_purchases --property print.key=true

```