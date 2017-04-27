[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/master/spark-logo-trademark.png" align="right">](https://spark.apache.org/)

# Awesome Spark [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Apache Spark](https://spark.apache.org/) packages and resources.


## Contents

- [Packages](#packages)
  - [DataSource Connector](#datasource-connector)
  - [Language Bindings](#language-bindings)
  - [Notebooks and IDEs](#notebooks-and-ides)
  - [General Purpose Libraries](#general-purpose-libraries)
  - [Bioinformatics](#bioinformatics)
  - [GIS](#gis)
  - [Time Series Analytics](#time-series-analytics)
  - [Graph Processing](#graph-processing)
  - [Computer Vision](#computer-vision)
  - [Machine Learning Extension](#machine-learning-extension)
  - [Middleware](#middleware)
  - [Utilities](#utilities)
  - [Natural Language Processing](#natural-language-processing)
  - [Interfaces](#interfaces)
  - [Profiling](#profiling)
  - [In Memory Layer](#in_memory_layer)

- [Related Project](#related-project)

- [Resources](#resources)
  - [Books](#books)
  - [Papers](#papers)
  - [MOOCS](#moocs)
  - [Workshops](#workshops)
  - [Projects Using Spark](#projects-using-spark)
  - [Blogs](#blogs)
  - [Docker Images](#docker-images)
  - [Miscellaneous](#miscellaneous)


## Packages
* Also refer to http://spark.apache.org/third-party-projects.html

### DataSource Connector
* [spark-avro](https://github.com/databricks/spark-avro) - A library for reading and writing Avro data from Spark SQL.
* [Apache Spark - Apache HBase Connector](https://github.com/hortonworks-spark/shc) - A library to support Spark accessing HBase table as external data source or sink. With it, user can operate HBase with Spark-SQL on data frame level.
* [Spark CSV](https://github.com/databricks/spark-csv) - CSV reader and writer (obsolete since Spark 2.0 [[SPARK-12833]](https://issues.apache.org/jira/browse/SPARK-12833)).
* [Spark XML](https://github.com/databricks/spark-xml) - XML parser and writer.
* [Spark-Mongodb](https://github.com/Stratio/Spark-MongoDB) - MongoDB reader and writer.
* [Spark Cassandra Connector](https://github.com/datastax/spark-cassandra-connector) - Cassandra support including data source and API and support for arbitrary queries.
* [Spark Riak Connector](https://github.com/basho/spark-riak-connector) - Riak TS & Riak KV connector.
* [Mongo-Spark](https://github.com/mongodb/mongo-spark) - Official MongoDB connector.
* [Apache Bahir](https://bahir.apache.org/) - Collection of the streaming connectors excluded from Spark 2.0 (Akka, MQTT, Twitter. ZeroMQ).

### Language Bindings

* [Flambo](https://github.com/yieldbot/flambo) - Clojure DSL.
* [Mobius](https://github.com/Microsoft/Mobius) - C# bindings.
* [sparklyr](https://github.com/rstudio/sparklyr) - An alternative R backend, using [`dplyr`](https://github.com/hadley/dplyr).
* [eclairjs-node](https://github.com/EclairJS/eclairjs-node) - EclairJS Node provides Node.js language bindings for Apache Spark.

### Notebooks and IDEs

* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) - Web-based notebook that enables interactive data analytics with plugable backends, integrated plotting, and extensive Spark support out-of-the-box.
* [Apache Toree](https://github.com/apache/incubator-toree) - The main goal of the Toree is to provide the foundation for interactive applications to connect to and use Apache Spark.
* [Spark Notebook](https://github.com/andypetrella/spark-notebook) - Scalable and stable Scala and Spark focused notebook bridging the gap between JVM and Data Scientists (incl. extendable, typesafe and reactive charts).
* [Jupyter-Scala](https://github.com/alexarchambault/jupyter-scala) - Lightweight Scala kernel for Jupyter that have good support on spark
* [sparkmagic](https://github.com/jupyter-incubator/sparkmagic) - [Jupyter](https://jupyter.org/) magics and kernels for working with remote Spark clusters, for interactively working with remote Spark clusters through [Livy](https://github.com/cloudera/livy), in Jupyter notebooks.

### General Purpose Libraries

* [Succinct](http://succinct.cs.berkeley.edu/) - Support for efficient queries on compressed data.

### Bioinformatics

* [ADAM](https://github.com/bigdatagenomics/adam) - Set of tools designed to analyse genomics data.
* [Hail](https://github.com/hail-is/hail) - Genetic analysis framework.

### GIS

* [Magellan](https://github.com/harsha2010/magellan) - Geospatial analytics using Spark.
* [GeoSpark](https://github.com/Sarwat/GeoSpark) - Cluster computing system for processing large-scale spatial data.

### Time Series Analytics

* [Spark-Timeseries](https://github.com/cloudera/spark-timeseries) - Scala / Java / Python library for interacting with time series data on Apache Spark.

### Graph Processing

* [Mazerunner](https://github.com/neo4j-contrib/neo4j-mazerunner) - Graph analytics platform on top of Neo4j and GraphX.
* [GraphFrames](https://github.com/graphframes/graphframes) - Data frame based graph API.
* [neo4j-spark-connector](https://github.com/neo4j-contrib/neo4j-spark-connector) - Bolt protocol based, Neo4j Connector with RDD, DataFrame and GraphX / GraphFrames support.

### Computer Vision
* [Thunder](https://github.com/thunder-project/thunder) - Thunder is an ecosystem of tools for the analysis of image and time series data in Python. It can be used locally, but also supports large-scale analysis through the distributed computing engine spark. 

### Machine Learning Extension

* [Apache SystemML](https://systemml.apache.org/) - Declarative machine learning framework on top of Spark.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) - linear algebra DSL and optimizer with R-like syntax. Originally on hadoop now supports spark.
* [spark-sklearn](https://github.com/databricks/spark-sklearn) - Scikit-learn integration with distributed model training.
* [KeystoneML](https://github.com/amplab/keystone) - Another software framework, written in Scala, from the AMPLab designed to simplify the construction of large scale, end-to-end, machine learning pipelines with Apache Spark.
* [Distributed Keras](https://github.com/cerndb/dist-keras) - Distributed deep learning framework with PySpark and Keras.
* [Elephas](https://github.com/maxpumperla/elephas) - Elephas is an extension of Keras, which allows you to run distributed deep learning models at scale with Spark. 
* [Sparkling Water](https://github.com/h2oai/sparkling-water) -  [H2O](http://www.h2o.ai/) interoperability layer.H2O scales statistics, machine learning, and math over Big Data.
* [MXNet on Spark](https://github.com/dmlc/mxnet/tree/master/scala-package/spark) - MXNet Scala Package and brings deep learning to Spark. You can take advantage of both the flexible parallel training approaches and GPU support with MXNet, and the fast data processing flow with Spark
* [CaffeOnSpark](https://github.com/yahoo/CaffeOnSpark) - By combining salient features from deep learning framework Caffe and big-data frameworks Apache Spark and Apache Hadoop, CaffeOnSpark enables distributed deep learning on a cluster of GPU and CPU servers.
* [TensorFlowOnSpark](https://github.com/yahoo/TensorFlowOnSpark) - Another tool by Yahoo that supports tensorflow.
* [BigDL](https://github.com/intel-analytics/BigDL) - BigDL is a distributed deep learning library for Apache Spark by Intel.


### Middleware

* [Livy](https://github.com/cloudera/livy) - REST server with extensive language support (Python, R, Scala), ability to maintain interactive sessions and object sharing.https://github.com/dmlc/mxnet/tree/master/scala-package/spark
* [spark-jobserver](https://github.com/spark-jobserver/spark-jobserver) - Simple Spark as a Service which supports objects sharing using so called named objects. JVM only.
* [Mist](https://github.com/Hydrospheredata/mist) - Service for exposing Spark analytical jobs and machine learning models as realtime, batch or reactive web services.
* [flintrock](https://github.com/nchammas/flintrock) - A command-line tool for launching Apache Spark clusters on AWS EC2.
* [spark-openstack](https://github.com/ispras/spark-openstack) - Scripts to setup Spark cluster (any version) in any Openstack environment with optional useful tools.

### Lambda Architecture
* [Oryx 2](https://github.com/OryxProject/oryx) - Lambda architecture on Apache Spark, Apache Kafka for real-time large scale machine learning

### Utilities

* [silex](https://github.com/willb/silex) - Collection of tools varying from ML extensions to additional RDD methods.
* [sparkly](https://github.com/Tubular/sparkly) - Helpers & syntactic sugar for PySpark.

### Natural Language Processing

* [spark-corenlp](https://github.com/databricks/spark-corenlp) - DataFrame wrapper for [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/).

### Interfaces

* [Apache Beam](https://beam.apache.org/) - Unified data processing engine supporting both batch and streaming applications. Apache Spark is one of the supported execution environments.
* [Blaze](https://github.com/blaze/blaze) - Interface for querying larger than memory datasets using Pandas-like syntax. It supports both Spark `DataFrames` and `RDDs`.

### Profilings

* [Memory Profiler](https://github.com/fabianp/memory_profiler) - Monitor Memory usage of Python code which can help to profiling pyspark.

### In Memory Layer

* [Alluxio](http://www.alluxio.org/) - Memory speed virtual distributed storage system that supports running Spark.
* [Apache Ignite](https://ignite.apache.org/) - Apache Ignite is a high-performance, integrated and distributed in-memory platform for computing and transacting on large-scale data sets that supports spark
* [SnappyData](https://www.snappydata.io/) - SnappyData is a high performance in-memory data platform for mixed workload applications. Built on Apache Spark, SnappyData provides a unified programming model for streaming, transactions, machine learning and SQL Analytics in a single cluster. 

## Related DataBase Project
* [Apache Kudu](https://kudu.apache.org/) - A new addition to the open source Apache Hadoop ecosystem, Apache Kudu completes Hadoop's storage layer to enable fast analytics on fast data.
* [Apache Parquet](https://github.com/apache/parquet-mr) -Parquet-MR contains the java implementation of the Parquet format. Parquet is a columnar storage format for Hadoop; it provides efficient storage and encoding of data. 
* [Apache Avro](https://github.com/apache/avro) - Apache Avro™ is a data serialization system and data format.
* [FiloDB](https://github.com/filodb/FiloDB) - FiloDB is a new open-source distributed, versioned, and columnar analytical database designed for modern streaming workloads.
* [BlinkDB](https://github.com/sameeragarwal/blinkdb) - BlinkDB is a large-scale data warehouse system built on Shark and Spark and is designed to be compatible with Apache Hive.


## Resources
### Books

* [Learning Spark, Lightning-Fast Big Data Analysis](http://shop.oreilly.com/product/0636920028512.do) - Slightly outdated (Spark 1.3) introduction to Spark API. Good source of knowledge about basic concepts.
* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do) - Useful collection of Spark processing patterns. Accompanying GitHub repository: [sryza/aas](https://github.com/sryza/aas).
* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/) - Interesting compilation of notes by [Jacek Laskowski](https://github.com/jaceklaskowski). Focused on different aspects of Spark internals.
* [Spark Gotchas](https://github.com/awesome-spark/spark-gotchas) - Subjective compilation of tips, tricks and common programming mistakes.
* [Spark in Action](https://www.manning.com/books/spark-in-action) - New book in the Manning's "in action" family with +400 pages. Starts gently, step-by-step and covers large number of topics. Free excerpt on how to [setup Eclipse for Spark application development](http://freecontent.manning.com/how-to-start-developing-spark-applications-in-eclipse/) and how to bootstrap a new application using the provided Maven Archetype. You can find the accompanying GitHub repo [here](https://github.com/spark-in-action/first-edition).
* [Apache Spark in 24 Hours, Sams Teach Yourself](https://www.amazon.com/Apache-Spark-Hours-Teach-Yourself/dp/0672338513/ref=as_li_ss_tl?s=books&ie=UTF8&qid=1484325855&sr=1-1&keywords=apache+spark+in+24+hours&linkCode=sl1&tag=matratsblo-20&linkId=2a8f9733bda37b66309efcded726ffd8) - Are you impatient? This book has been written for you!
* [Spark: Big Data Cluster Computing in Production](https://www.amazon.com/Spark-Data-Cluster-Computing-Production/dp/1119254019/ref=as_li_ss_tl?s=english-books&ie=UTF8&qid=1484325979&sr=1-1&keywords=spark:+Big+Data+Cluster+Computing+in+Production&linkCode=sl1&tag=matratsblo-20&linkId=9126f54ac279119937a742af01871837) - If you are already a data engineer and want to learn more about production deployment for Spark apps, this book is a good start. You’ll learn how to monitor your Spark clusters, work with metrics, resource allocation, object serialization with Kryo, more. 
* [High Performance Spark: Best Practices for Scaling and Optimizing Apache Spark](https://www.amazon.com/High-Performance-Spark-Practices-Optimizing/dp/1491943203/ref=as_li_ss_tl?ie=UTF8&linkCode=sl1&tag=matratsblo-20&linkId=52f86ff4f5e2e0be6da42009cbe07d52) - Again written in part by Holden Karau, High Performance Spark focuses on data manipulation techniques using a range of spark libraries and technologies above and beyond core RDD manipulation. 


### Papers
* Also refers to http://spark.apache.org/research.html
* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://people.csail.mit.edu/matei/papers/2012/nsdi_spark.pdf) - Paper introducing a core distributed memory abstraction.
* [Spark SQL: Relational Data Processing in Spark](https://amplab.cs.berkeley.edu/wp-content/uploads/2015/03/SparkSQLSigmod2015.pdf) - Paper introducing relational underpinnings, code generation and Catalyst optimizer.

### MOOCS

* [Data Science and Engineering with Apache Spark (edX XSeries)](https://www.edx.org/xseries/data-science-engineering-apache-spark) - Series of five courses ([Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x), [Distributed Machine Learning with Apache Spark](https://www.edx.org/course/distributed-machine-learning-apache-uc-berkeleyx-cs120x), [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x), [Advanced Apache Spark for Data Science and Data Engineering](https://www.edx.org/course/advanced-apache-spark-data-science-data-uc-berkeleyx-cs115x), [Advanced Distributed Machine Learning with Apache Spark](https://www.edx.org/course/advanced-distributed-machine-learning-uc-berkeleyx-cs125x)) covering different aspects of software engineering and data science. Python oriented.
* [Big Data Analysis with Scala and Spark (Coursera)](https://www.coursera.org/learn/big-data-analysys) - Scala oriented introductory course. Part of [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu) - Periodical training event organized by the [UC Berkeley AMPLab](https://amplab.cs.berkeley.edu/). A source of useful exercise and recorded workshops covering different tools from the [Berkeley Data Analytics Stack](https://amplab.cs.berkeley.edu/software/).

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) - [Lambda architecture](http://lambda-architecture.net/) platform built on Apache Spark and [Apache Kafka](http://kafka.apache.org/) with specialization for real-time large scale machine learning.
* [Photon ML](https://github.com/linkedin/photon-ml) - A machine learning library supporting classical Generalized Mixed Model and Generalized Additive Mixed Effect Model.
* [PredictionIO](https://prediction.io/) - Machine Learning server for developers and data scientists to build and deploy predictive applications in a fraction of the time.
* [Crossdata](https://github.com/Stratio/Crossdata) - Data integration platform with extended DataSource API and multi-user environment.

### Blogs

- [Spark Technology Center](http://spark.tc/blog/) - Great source of highly diverse posts related to Spark ecosystem. From practical advices to Spark commiter profiles.

### Docker Images

- [jupyter/docker-stacks/pyspark-notebook](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) - PySpark with Jupyter Notebook and Mesos client.
- [sequenceiq/docker-spark](https://github.com/sequenceiq/docker-spark) - Yarn images from [SequenceIQ](http://www.sequenceiq.com/).

### Miscellaneous

- [Spark with Scala Gitter channel](https://gitter.im/spark-scala/Lobby) - "_A place to discuss and ask questions about using Scala for Spark programming_" started by [@deanwampler](https://github.com/deanwampler).
- [Apache Spark User List](http://apache-spark-user-list.1001560.n3.nabble.com/) and [Apache Spark Developers List](http://apache-spark-developers-list.1001551.n3.nabble.com/) - Mailing lists dedicated to usage questions and development topics respectively.

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="http://i.creativecommons.org/p/mark/1.0/88x31.png"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br />
This work (<span property="dct:title">Awesome Spark</span>, by <a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">https://github.com/awesome-spark/awesome-spark</a>), identified by <a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>, is free of known copyright restrictions.
</p>

Apache Spark, Spark, Apache, and the Spark logo are <a href="https://www.apache.org/foundation/marks/">trademarks</a> of
  <a href="http://www.apache.org">The Apache Software Foundation</a>. This compilation is not endorsed by The Apache Software Foundation.
