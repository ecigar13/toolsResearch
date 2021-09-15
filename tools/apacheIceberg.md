# Apache Iceberg

### What is it?
An abstraction layer on top of Hive (SQL engine). Think of it as abstracting data to a table format for simpler querying. It has more syntactic sugar and automates some of the work for you.

### Pros
- Hidden partition: handles Hive column partitioning automatically, handle error, so user spend less time wrangling data.
    - Example: UTC date into smaller fields.
- Schema evolution: add some features typical of SQL such as add, drop, update...
- Version roll back, reproducible queries.

### Cons
- Typical for abstraction layers: easier to use, less fine-grained control.

### Compared to similar tools
To Hudi, Delta...: less dependent on Spark when it comes to writing.
Over time, many of these tools will die out and only a few left.