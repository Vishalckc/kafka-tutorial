# kafka-tutorial
This kafka tutorial provides both producer and consumer classes with a sample topic "exampletopic" exposed over  a Restful API api/v1/messages
using Apache Zookeeper, Kafka broker, producer, consumer and Kafka rest template

https://kafka.apache.org/documentation/#quickstart

**1 Download Kafka**

**2 Run Zookeeper with config**

**3 Start Kafka Broker**

**4 Create a Kafka topic**

**5 Producer publishes on messages to the broker on the above topic**

**6 Conusmer listens for this topic with same server config**

**How to Run** -

Run KafkaApplication main class (default port 8080)

**How to test?**

Use postman for API operations

Sample Json Request below:

URL- http://localhost:8080/api/v1/messages

Request Body 
{
    "message" : "New API message"
}

ContentType- Application/JSON

Response
200 OK
