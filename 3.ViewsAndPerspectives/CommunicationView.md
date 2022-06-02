Microservices or modules are decoupled from each other but still able to communicate. Cross dependencies are typical for a microservice architecture, meaning no single service can perform without getting help from other services.

Each microservice has the responsibility to do a simple task and return the result to the underlying messaging system so that another microservice continues the job. The communication between the microservices is done via RabbitMQ queues, which results in a microservice consuming data from a queue and publishing the outcome to another queue. As a result, a chain of microservices processes the requests.

ADR we use rabbitmq
