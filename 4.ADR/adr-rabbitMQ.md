# We use RabbitMQ

Date: 2022-06-02

# Status
Accepted

# Context
We need distributed event store and stream-processing platform

# Decision

# Consequences
Positive:

- RabbitMQ is best for simple use cases.
- RabbitMQ is much more flexible and easy to use in these circumstances as compared to Kafka.
- RabbitMQ is language-agnostic, which means that you can create microservice in different languages, and RabbitMQ will still support such an architecture. RabbitMQ provides more language integrations than Kafka.

Negative:

- As Kafka is designed to handle high volumes of data, it’s overkill if you need to process only a small amount of messages per day (up to several thousand). Use traditional message queues such as RabbitMQ for relatively smaller data sets or as a dedicated task queue.

# Risks:
- high volumes of data
