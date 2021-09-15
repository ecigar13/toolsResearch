# Kafka

### What it is?
A distributed streaming platform, very scalable. Emphasis on distributed. This distinguishes it from ActiveMQ, RabbitMQ.

### Pros
- Focused on high throughput
- Scalable, hundred of thousands of messages (300k+)
- Guarantee ordered messages
- Reliable when set up as a cluster
- Read messages are still available

### Cons
- Must use Zookeeper
- Hard to set up and maintain
- No visibility from observability point of view.
- Very customizable, but no preset. 

### Compared to similar tools
Give me a size XXXL. Non Big-N companies need not apply.