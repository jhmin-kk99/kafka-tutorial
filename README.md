# kafka-tutorial
kafka-tutorial   
      
## **Install and Set up Kafka**
[https://kafka.apache.org/quickstart]

**STEP 1: DOWNLOAD AND INSTALL KAFKA**
[https://dlcdn.apache.org/kafka/3.2.0/kafka_2.13-3.2.0.tgz](https://www.apache.org/dyn/closer.cgi?path=/kafka/3.6.0/kafka_2.13-3.6.0.tgz)   

**STEP 2: START THE KAFKA ENVIRONMENT**      
   
*Start the ZooKeeper service*   
For windows

```
C:GO TO KAFKA DIR>.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
```
*start the Kafka broker service*   
```
C:GO TO KAFKA DIR>.\bin\windows\kafka-server-start.bat .\config\server.properties
```
**STEP 3: CREATE A TOPIC TO STORE YOUR EVENTS** 
```
C:GO TO KAFKA DIR>.\bin\windows\kafka-topics.bat --create --topic topic_demo --bootstrap-server localhost:9092
```
**STEP 4: WRITE SOME EVENTS INTO THE TOPIC**
```
C:GO TO KAFKA DIR>.\bin\windows\kafka-console-producer.bat --topic topic_demo --bootstrap-server localhost:9092
hello world
topic demo
```
**STEP 5:  READ THE EVENTS**
```
C:GO TO KAFKA DIR>.\bin\windows\kafka-console-consumer.bat --topic topic_demo --from-beginning --bootstrap-server localhost:9092
```
For Mac   
Go to a link 
[https://kafka.apache.org/quickstart]
