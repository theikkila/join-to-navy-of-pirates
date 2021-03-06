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
- [ ] Save aggregates where there is counts of distinct events as JSON-lines (look what `coalesce()` and `repartition()` does)
- [ ] Why you shouldn't use Spark?
- [ ] What is an EMR?
### Bonus
- [ ] What is a shuffle? (http://hydronitrogen.com/apache-spark-shuffles-explained-in-depth.html)
- [ ] Write SQL-version of counts of distinct events
- [ ] Read https://databricks.com/blog/2016/11/14/setting-new-world-record-apache-spark.html


## Task 2: Apache Kafka

Make yourself familiar with Apache Kafka (https://kafka.apache.org/)

- [ ] What is Kafka? How it's different from RabbitMQ or Redis pubsub (!! pubsub not streams!)?
- [ ] Read this (https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
- [ ] Read also this http://antirez.com/news/114
- [ ] Kafka uses Zookeeper - what it is?
- [ ] Do the Kafka quickstart and ingest some data into it, then process it out
- [ ] What is Kafka good for?
- [ ] What are alternatives to Kafka?
- [ ] Read https://www.confluent.io/blog/exactly-once-semantics-are-possible-heres-how-apache-kafka-does-it/
- [ ] What is `exacly once` semantics? Why it is hard to implement?
- [ ] Why you shouldn't use Kafka?
- [ ] What are alternative products from AWS and Google?
- [ ] Read about reliability of Kafka from Aphyr's blog (https://aphyr.com/posts/293-jepsen-kafka)
- [ ] Read also about Zookeeper's reliability from Aphyr's blog (https://aphyr.com/posts/291-jepsen-zookeeper)


### Bonus
- [ ] How Apache Kafka scales? What are partitions? Topics?
- [ ] New features of Kafka includes KSQL, read more about it (https://www.confluent.io/blog/ksql-open-source-streaming-sql-for-apache-kafka/)
- [ ] Read about **kappa** architecture (http://milinda.pathirage.org/kappa-architecture.com/)

## Task 3: Apache Cassandra

Make yourself familiar with Apache Cassandra (https://www.datastax.com/2012/01/getting-started-with-cassandra)

- [ ] What it is? How it's different from MySQL, PostgreSQL, MongoDB or Redis?
- [ ] What is the data storage model of Cassandra
- [ ] Search for `what cassandra is good for`
- [ ] Why you shouldn't use Cassandra?
- [ ] How it's different from HBASE?
- [ ] DynamoDB vs. Cassandra?
- [ ] Read how Reddit was using Cassandra for r/Place (https://redditblog.com/2017/04/13/how-we-built-rplace/)
- [ ] But WHY?!
- [ ] Read about reliability of Cassandra from Aphyr's blog (https://aphyr.com/posts/294-jepsen-cassandra)

### Bonus
- [ ] Install Cassandra into container
- [ ] Write small application that updates key-value pairs (see https://github.com/theikkila/join-to-navy-of-pirates/blob/master/excercises/playtracker.md)

## Task 4: Elasticsearch

Make yourself familiar with Elasticsearch (https://www.elastic.co/)

- [ ] Install Elasticsearch (ie. with docker)
- [ ] Ingest Blok.ai listing data into that (https://app.blok.ai/integrations/listing/feed/blok/json) so you can search from it.
- [ ] Create small script with any language that you can use to query previous api items from the elasticsearch
- [ ] What is Elasticsearch good for?
- [ ] What else there is if you need to have search engine for your data?
- [ ] How does search engine indices work?
- [ ] Read about reliability of ES from Aphyr's blog (https://aphyr.com/posts/323-jepsen-elasticsearch-1-5-0)


## Task 5: MapReduce

- Read best possible introduction to MR from here (https://www.kchodorow.com/blog/2010/03/15/mapreduce-the-fanfiction/)
- Implement following operations using just `map` and `reduce` steps:
   - group by
   - filter
   - join

## Task 6: Hadoop & HDFS
- Yarn
- HDFS
- Pig
- Namenode & Datanode
- S3 vs HDFS

## Task 7: Hive & Presto
- Amazon Athena

## Task 8: Metabase
- Install
- Try it out
- What it is?

## Task 9: Superset
- Install
- Try it out
- What it is?

## Task 10: Grafana
- Install
- Try it out
- What it is?

## Task 11: InfluxDB
- Alternatives?
- Read about TICK-stack
- When you should use InfluxDB?
- Find out what kind of data model influxdb is using

## Task 12: Redis
- What it is?
- Code simple alternative (just Key-Value functionality, no TTL)
- Hosted?
- Compare to Memcached
- What it is good for?
- Write test application using redis (https://github.com/theikkila/join-to-navy-of-pirates/blob/master/excercises/playtracker.md)


## Task 13: Squoop
http://sqoop.apache.org/docs/1.99.7/user/Sqoop5MinutesDemo.html

## Task 14: Zeppelin
- What it is?
- Can I use it in EMR?
- Install and try the spark tasks with zeppelin
- Plot hourly event count with Zeppelin

## Task 15: Kubernetes

- Basics
- Manifests
- Hosted?
- Alternatives?
- What is etcd used for?

## Task 16: Maxwell's daemon & CDC
https://www.confluent.io/blog/turning-the-database-inside-out-with-apache-samza/

## Task 17: Data Modeling
- Snowflake
- Star
- Data Vault 2.0
- Normalized or Denormalized

## Task 18: Data transport
- For all of these:
  - find out what they are used for
  - how they're different from each other?
  - do they use types?
  - Pros/Cons?
- JSON
- Avro
- Protobuf (see also GRPC)
- Cap’n Proto
- MessagePack
- Transit (it's clojure stuff)
- XML (see also SOAP)
- YAML


## Task 19: Data storage
- Data lake?
- EDW?
- Data mart?
- OLAP/OLTP?
- Column oriented vs. Row oriented
- Redshift?
- Kudu/Impala?
- Parquet, ORC, AVRO, JSON - make a grand comparision!
- What kind of effect compression has?

## Task 20: Distributed systems
- Etcd
- CAP-theorem
- Read aphyr's blog
   - Start from here, continue until exhausted: https://aphyr.com/posts/333-serializability-linearizability-and-locality
- Find out what is Jepsen test
- How to debug distributed systems: https://github.com/jaegertracing/jaeger
- Read how overengineering can be done with reliable components: https://eng.uber.com/schemaless-part-one/
- Why they need that? Pros and cons?

## Task 21: Serverless
- Lambda?
- Cloud functions with Firebase

## Task 22: Graph databases
- Neo4j
- OrientDB
- Graph algorithms

## Task 23: Relational databases
- Mysql, Mariadb, postgresql, oracle, sql server, amazon rds, amazon aurora

## Task 24: RabbitMQ
- Amazon SQS?

## Task 25: Scalability and architecture
- [ ] Read http://highscalability.com/blog/2013/8/26/reddit-lessons-learned-from-mistakes-made-scaling-to-1-billi.html 
- [ ] Admit that PostgreSQL is always a wise choice!
