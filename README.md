# A basic demonstration of Apache Kafka implementation
This project comprises a producer and a consumer component, seamlessly leveraging Kafka's messaging capabilities. The producer module utilizes a REST API to send requests, while the consumer module efficiently prints received messages from Kafka to the console. This project serves as a reliable and concise introduction to Apache Kafka, showcasing its practical use in building robust messaging systems.

Also the CommandLineRunner implementation executes the code inside its run method which sends a series of messages to a Kafka topic using the kafkaTemplate. It sends messages with the content "hello kafka " followed by a number from 0 to 100. You can change it to 1_000_000 to see how fast is Kafka.
