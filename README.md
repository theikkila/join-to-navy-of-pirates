# join-to-navy-of-pirates


## Task 1: Apache Spark

Make yourself familiar with Apache Spark (https://spark.apache.org/)

Dataset: https://github.com/emblica/sessionization/blob/master/events.json.tar.gz

- [ ] What is pyspark? How it is related to normal spark?
- [ ] Read JSON-lines with pyspark using pyspark shell (read https://spark.apache.org/docs/latest/sql-programming-guide.html)
- [ ] Use Spark to execute custom SQL-queries on top of the JSON-data (https://spark.apache.org/docs/latest/sql-programming-guide.html#running-sql-queries-programmatically)
- [ ] What is parquet?
- [ ] Save JSON-lines as parquet file
- [ ] Read Parquet-file of JSON-lines into spark
- [ ] Save aggregates where there is count of distinct events as JSON-lines (look what `coalesce()` and `repartition()` does)
- [ ] Why you shouldn't use Spark?

## Task 2: Apache Kafka

Make yourself familiar with Apache Kafka (https://kafka.apache.org/)

- [ ] What is Kafka? How it's different from RabbitMQ or Redis pubsub?
- [ ] Kafka uses Zookeeper - what it is?
- [ ] Do the Kafka quickstart and ingest some data into it, then process it out
- [ ] What is Kafka good for?
- [ ] What are alternatives to Kafka?
- [ ] Read https://www.confluent.io/blog/exactly-once-semantics-are-possible-heres-how-apache-kafka-does-it/
- [ ] What is `exacly once` semantics? Why it is hard to implement?
- [ ] Why you shouldn't use Kafka?

## Task 3: Apache Cassandra

Make yourself familiar with Apache Cassandra (https://www.datastax.com/2012/01/getting-started-with-cassandra)

- [ ] What it is? How it's different from MySQL, PostgreSQL, MongoDB or Redis?
- [ ] What is the data storage model of Cassandra
- [ ] Search for `what cassandra is good for`
- [ ] Why you shouldn't use Cassandra?
