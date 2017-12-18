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
- [ ] What is an EMR?

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
- [ ] What are alternative products from AWS and Google?

## Task 3: Apache Cassandra

Make yourself familiar with Apache Cassandra (https://www.datastax.com/2012/01/getting-started-with-cassandra)

- [ ] What it is? How it's different from MySQL, PostgreSQL, MongoDB or Redis?
- [ ] What is the data storage model of Cassandra
- [ ] Search for `what cassandra is good for`
- [ ] Why you shouldn't use Cassandra?
- [ ] How it's different from HBASE?
- [ ] DynamoDB vs. Cassandra?

## Task 4: Elasticsearch

Make yourself familiar with Elasticsearch (https://www.elastic.co/)

- [ ] Install Elasticsearch (ie. with docker)
- [ ] Ingest Blok.ai listing data into that (https://app.blok.ai/integrations/listing/feed/blok/json) so you can search from it.
- [ ] Create small script with any language that you can use to query previous api items from the elasticsearch
- [ ] What is Elasticsearch good for?
- [ ] What else there is if you need to have search engine for your data?
- [ ] How does search engine indices work?


## Task 5: MapReduce

## Task 6: Hadoop & HDFS
- Yarn
- HDFS
- Pig
- Namenode & Datanode
- S3 vs HDFS

## Task 7: Hive & Presto
- Amazon Athena

## Task 8: Metabase

## Task 9: Superset

## Task 10: Grafana

## Task 11: InfluxDB
- Alternatives?

## Task 12: Redis
- Simple alternative?
- Hosted?

## Task 13: Squoop
http://sqoop.apache.org/docs/1.99.7/user/Sqoop5MinutesDemo.html

## Task 14: Zeppelin
- Can I use it in EMR?

## Task 15: Kubernetes

- Basics
- Manifests
- Hosted alternatives?

## Task 16: Maxwell's daemon & CDC
https://www.confluent.io/blog/turning-the-database-inside-out-with-apache-samza/

## Task 17: Data Modeling
- Snowflake
- Star
- Data Vault 2.0
- Normalized or Denormalized

## Task 18: Data storage
- Data lake?
- EDW?
- Data mart?
- OLAP/OLTP?
- Column oriented vs. Row oriented
- Redshift?
- Kudu/Impala?
- 

## Task 19: Distributed systems
- Etcd
- CAP-theorem
- https://github.com/jaegertracing/jaeger
- https://eng.uber.com/schemaless-part-one/

## Task 20: Serverless
- Lambda?
- Cloud functions with Firebase

## Task 21: Graph databases
- Neo4j
- OrientDB
- Graph algorithms

## Task 22: Relational databases
- Mysql, Mariadb, postgresql, oracle, sql server, amazon rds, amazon aurora

## Task 23: RabbitMQ
- Amazon SQS?

