# Awesome DataLake

This repository contains a curated list of awesome data lake frameworks.

## Lakehouse

* [Apache Amoro](https://github.com/apache/amoro) - Apache Amoro (incubating) is a Lakehouse management system built on open data lake formats.
* [LakeSoul](https://github.com/lakesoul-io/LakeSoul) - LakeSoul is an end-to-end, realtime and cloud native Lakehouse framework with fast data ingestion, concurrent update and incremental data analytics on cloud storages for both BI and AI applications.
* [OpenHouse](https://github.com/linkedin/openhouse) - Open Control Plane for Tables in Data Lakehouse.
* [Geolake](https://github.com/spatialx-project/geolake) - Universal solution for geospatial data tailored to data lakehouse systems for the first time in the industry.
* [LHBench](https://github.com/lhbench/lhbench) - Lakehouse storage system benchmark.

## Open Table Formats

* [Apache Hive](https://github.com/apache/hive) - The Apache Hive (TM) data warehouse software facilitates reading, writing, and managing large datasets residing in distributed storage using SQL.
* [Apache Hudi](https://github.com/apache/hudi) - Upserts, Deletes And Incremental Processing on Big Data.
* [Apache Iceberg](https://github.com/apache/iceberg) - Iceberg is a high-performance format for huge analytic tables. Iceberg brings the reliability and simplicity of SQL tables to big data, while making it possible for engines like Spark, Trino, Flink, Presto, Hive and Impala to safely work with the same tables, at the same time.
* [Apache Paimon](https://github.com/apache/paimon) - Apache Paimon is a lake format that enables building a Realtime Lakehouse Architecture with Flink and Spark for both streaming and batch operations.
* [Apache XTable](https://github.com/apache/incubator-xtable) - Apache XTable (incubating) is a cross-table converter for lakehouse table formats that facilitates interoperability across data processing systems and query engines.
* [Delta Lake](https://github.com/delta-io/delta/): An open-source storage framework that enables building a Lakehouse architecture with compute engines including Spark, PrestoDB, Flink, Trino, and Hive and APIs

## File Formats

* [Apache Avro](https://github.com/apache/avro) - Apache Avro is a data serialization system.
* [Apache ORC](https://github.com/apache/orc) - ORC is a self-describing type-aware columnar file format designed for Hadoop workloads. 
* [Apache Parquet](https://github.com/apache/parquet-format) - Apache Parquet is an open source, column-oriented data file format designed for efficient data storage and retrieval. It provides high performance compression and encoding schemes to handle complex data in bulk and is supported in many programming language and analytics tools.
* CSV
* JSON

## Data Lake Storages

**HCFS (Hadoop Compatible File System):**

* [HDFS](https://github.com/apache/hadoop/tree/trunk/hadoop-hdfs-project) - The Hadoop Distributed File System (HDFS) is a distributed file system designed to run on commodity hardware. 
* [Minio](https://github.com/minio/minio) - MinIO is a High Performance Object Storage released under GNU Affero General Public License v3.0. It is API compatible with Amazon S3 cloud storage service.

**DVC (Data Version Control):**

* [lakeFS](https://github.com/treeverse/lakeFS) - lakeFS is an open-source tool that transforms your object storage into a Git-like repository. It enables you to manage your data lake the way you manage your code.
* [DVC](https://github.com/iterative/dvc) - ML Experiments and Data Management with Git
* [Nessie](https://github.com/projectnessie/nessie) - Project Nessie is a Transactional Catalog for Data Lakes with Git-like semantics.

**Cache:**

* [Alluxio](https://github.com/Alluxio/alluxio) - data orchestration for analytics and machine learning in the cloud.

## Data Lake Engines

* [Apache Flink](https://github.com/apache/flink) - Apache Flink is an open source stream processing framework with powerful stream- and batch-processing capabilities.
* [Apache Hive](https://github.com/apache/hive) - The Apache Hive (TM) data warehouse software facilitates reading, writing, and managing large datasets residing in distributed storage using SQL.
* [Apache Sedona](https://github.com/apache/sedona) - A cluster computing framework for processing large-scale geospatial data.
* [Apache Spark](https://github.com/apache/spark) - Spark is a unified analytics engine for large-scale data processing. 
* [Dremio](https://github.com/dremio/dremio-oss) - Dremio is a next-generation data lake engine that liberates your data with live, interactive queries directly on cloud data lake storage, including S3 and lakeFS.
* [Presto](https://github.com/prestodb/presto) - Presto is a distributed SQL query engine for big data.
* [Trino](https://github.com/trinodb/trino) - Trino is a fast distributed SQL query engine for big data analytics.

## Data Lake Tools

* [Smart Data Lake](https://github.com/smart-data-lake/smart-data-lake) - Smart Automation Tool for building modern Data Lakes and Data Pipelines
* [Kylo](https://github.com/Teradata/kylo) - Kylo is a data lake management software platform and framework for enabling scalable enterprise-class data lakes on big data technologies such as Teradata, Apache Spark and/or Hadoop. Kylo is licensed under Apache 2.0. Contributed by Teradata Inc
* [Cuelake](https://github.com/cuebook/cuelake) - Use SQL to build ELT pipelines on a data lakehouse.

## Unified Data Catalog

* [Apache Gravitino](https://github.com/apache/Gravitino) - Apache Gravitino is a high-performance, geo-distributed, and federated metadata lake. It manages the metadata directly in different sources, types, and regions. It also provides users with unified metadata access for data and AI assets.
* [Metacat](https://github.com/Netflix/metacat) - Metacat is a unified metadata exploration API service. You can explore Hive, RDS, Teradata, Redshift, S3 and Cassandra. 
* [Unity Catalog](https://github.com/unitycatalog/unitycatalog) - Open, Multi-modal Catalog for Data & AI.

## Security

* [Kerberos](https://web.mit.edu/kerberos/) - The Network Authentication Protocol.
* [Apache Ranger](https://github.com/apache/ranger) - To enable, monitor and manage comprehensive data security across the Hadoop platform and beyond.

## AI

* [Horovod](https://github.com/horovod/horovod) - Distributed training framework for TensorFlow, Keras, PyTorch, and Apache MXNet.
* [Petastorm](https://github.com/uber/petastorm) - Petastorm library enables single machine or distributed training and evaluation of deep learning models from datasets in Apache Parquet format. It supports ML frameworks such as Tensorflow, Pytorch, and PySpark and can be used from pure Python code.
* [Databricks’ Dolly](https://github.com/databrickslabs/dolly) - Databricks’ Dolly, a large language model trained on the Databricks Machine Learning Platform.
* [DeepLake](https://github.com/activeloopai/deeplake) - About Database for AI. Store Vectors, Images, Texts, Videos, etc.
