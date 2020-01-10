# Spring Boot project to send messages to Amazon SQS

This is a simple Spring Boot project to send messages to an Amazon SQS queue.

## How to run

After you clone this repo, build the project using the command below:

```shell script
mvn clean install
``` 

This will build the project and create a ```.jar``` file in the ```target/``` directory. Then run the following command 
to run the project:

```shell script
java -jar target/AmazonSQSProducerPOC-1.0-SNAPSHOT.jar
```