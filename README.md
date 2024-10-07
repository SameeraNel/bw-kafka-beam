Build the following with Apache Beam using Flink runner (but for the demo you can use DirectRunner).

1.           Build a Kafka streamer that reads from 1 topic and publish into 2 different topics
2.           Input topic will have a payload of first name, last name, date of birth.
3.           Logic: when age is even number, publish to topic: CustomerEVEN, if age is odd number, publish to topic: CustomerODD
4.           Build using Maven/Gradle and Spring Boot.
 
Bonus points:

1.           Containerised
2.           Unit tested
3.           JDK 17+
