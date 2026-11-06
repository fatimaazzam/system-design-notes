# Apache Kafka
## 1. Introduction
### What is Apache Kafka?
Apache Kafka is an open-source, distributed event streaming platform used to collect, store, and process streams of events in real time.
#### 1. What is an event?
    An event is a record of something that happened in a system.

    For example, in an e-commerce application:
    - A customer placed an order.
    - A payment was completed.
    - A user registered.
    - A product was shipped.

    Each of these is an event.

    An event describes something that has already happened.
#### 2. What does event streaming mean?
    Event streaming means continuously capturing, storing, and processing events as they happen.

    For example:
    1. A customer places an order.
    2. The application generates an OrderCreated event.
    3. The event is sent to Kafka.
    4. Other services can consume and process it.

#### 3. What does distributed mean?
    Kafka can run across multiple servers called brokers, working together as one cluster.

    This helps Kafka handle large amounts of data, scale, and tolerate server failures.

![Kafka event flow](images/kafka-flow.png)
### What is Kafka?

### What problem does it solve?

### Why do we need it?

## 2. Architecture

### Kafka Cluster

### Brokers

### Topics

### Partitions

## 3. How Kafka Works

## 4. Advantages and Disadvantages

## 5. Real-world Use Cases

## 6. Practical Examples

## 7. References