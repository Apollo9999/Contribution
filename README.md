RabbitMQ is famous for its documentation management, and its program codes are easy to be adapted. The installation was also easy. Topics are overall easy to be created by the web interface. Although good performance, the behavior is not compatible with the my system requirements.

Kafka has been designed originally by LinkedIn, and is written in Java. Kafka has very special architecture to me, where you can store messages in flat files. The server is very simple so makes it very fast to operate. Old messages can be retained regularly. However to me Kafka is not good at synchronizing and launching large sets of data, so you may need additional tool to help you. Overall, Kafka is good for low resource usage.

Here you can see a more clear list for the main difference of these two figures.

Difference in Open Source:

RabbitMQ: Mozilla Public License
Kafka: Apache License 2.0
Difference in Language:

RabbitMQ: Erlang
Kafka: Scala (JVM)
Federated Queues:

Yes for RabbitMQ and No for Kafka
Scaling Methods:

