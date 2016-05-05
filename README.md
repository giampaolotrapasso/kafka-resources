# General

#### The Log: What every software engineer should know about real-time data's unifying abstraction
The milestone post by Jay Kreps. Read this first! [Post](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)

#### Message Distribution and Topic Partitioning in Kafka
An introductory post on Kafka topic ("kTopic") and partitioning
[Post](http://www.jakubkorab.net/2015/12/message-distribution-and-topic-partitioning-in-kafka.html)

# Replication

### Hands-free Kafka Replication: A lesson in operational simplicity
High level post on basics of Replication
[Post](http://www.confluent.io/blog/hands-free-kafka-replication-a-lesson-in-operational-simplicity/)

### Intra-cluster Replication for Apache Kafka
An introductory video on Kafka by Jun Rao. This video introduces Kafka and focuses on the Kafka replication design with a detailed example of replica recovery. Kafka version: 0.8. [[Slides](http://www.slideshare.net/junrao/kafka-replication-apachecon2013)|[Video](https://youtu.be/XcvHmqmh16g)]

Index of video:
* [Introduction and Overview](https://youtu.be/XcvHmqmh16g)
* [Kafka architecture](https://youtu.be/XcvHmqmh16g?t=10m50s)
* [Kafka Replication design](https://youtu.be/XcvHmqmh16g?t=18m50s)
* [Handling follower failure](https://youtu.be/XcvHmqmh16g?t=32m20s)
* [Handling leader failure](https://youtu.be/XcvHmqmh16g?t=33m45s)
* [Example of replica recovery](https://youtu.be/XcvHmqmh16g?t=36m30s)
* [Performance](https://youtu.be/XcvHmqmh16g?t=40m29s)





# Delivery guarantees

####  Message delivery semantics on documentation
[Official documentation](http://kafka.apache.org/documentation.html#semantics)

#### Delivery guarantees on Kafka FAQ
[Delivery guarantees on FAQ](https://cwiki.apache.org/confluence/display/KAFKA/FAQ#FAQ-HowdoIgetexactly-oncemessagingfromKafka?)

#### Exactly-Once Delivery May Not Be What You Want
Not strictly related to Kafka but important to get the big picture. [Post](http://brooker.co.za/blog/2014/11/15/exactly-once.html)

#### Jakob Korab - Magical Messaging Fabric
This talk compares and contrasts the approaches taken by two similar but fundamentally different messaging platforms – Apache ActiveMQ and Apache Kafka. It discusses how their underlying philosophies impact message distribution, reliability, scalability, and performance.
[Video](https://www.youtube.com/watch?v=-31XLjlt3wc)
