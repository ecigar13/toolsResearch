# ActiveMQ


### What is it?
Message broker implementing AMQP, written in Java using Java Messaging Service. 

### Pros
- Easier to use than Kafka, out of the box configuration
- Has some ways to monitor the tool.

### Cons
- Lower throughput: less messages, and slower speed
- Can't  handle huge volume of messages (but it can handle most usecases)
- No emphasis on distributed system, mostly used for communication between microservices.

### Compared to similar tools
One size fits most (usecases)