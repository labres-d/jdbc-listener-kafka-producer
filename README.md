# JDBC Listener for Kafka Producer
This project tries to solve a problem in applications that use JDBC or JPA connections but desire to move to an event-driven architecture using Kafka. Without the necessity of creating Kafka Producers for different entities, this project uses the listeners from the JDBC to automatically create the event when an object is changed in the persistence layer.
