# Kafka consumer in Rust

This is kafka consumer made to be used with this [producer](https://github.com/DanielKneipp/rust-kafka-producer).
While that project produces messages to a topic, this one reads them. This project is
heavily based on this [example](https://github.com/fede1024/rust-rdkafka/blob/master/examples/simple_consumer.rs)
from `rdkafka` docs.

To execute it you can use binary directly like this:

```
./consumer -b <broker-url> -t <topic> -g <group-id>
```

You can also debug the executable using the target *"Debug executable 'consumer'"*
on vscode.
