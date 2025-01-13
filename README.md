# rabbit-mq-with-scala
Created a basic project in scala where a producer sends message to consumer using rabbit mq
--------------------
The Producer sends a "Hello" message to the RabbitMQ Queue name "greet" and the Consumer App consumes from this queue and prints it on the console.

## Steps to run the project

1. Navigate inside the Producer app and up the docker file to start the RabbitMQ using the given command
   docker-compose -f docker-compose.yml up

2. Start the Consumer App using the given command
    sbt run

3. Then start the Producer App using the given command
   sbt run



