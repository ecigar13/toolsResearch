# Hive

### What it is?
It a query engine for MapReduce, interacting with HDFS (Hadoop). Data warehouse tool

### Pros
- Helps querying HDFS
- Converts MapReduce job into jobs with dependency order

### Cons
- It runs MapReduce, so it's inherently slow
- Must use Zookeeper
- Can't help with OLTP or anything require fast response

### Compared to similar tools
Does things similar to SQL, but uses Hive Query Language (HQL), so SQL users are a bit more familiar with it.