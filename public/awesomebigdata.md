# Awesome Big Data

A curated list of awesome big data frameworks, ressources and other awesomeness. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [awesome-ruby](https://github.com/Sdogruyol/awesome-ruby), [hadoopecosystemtable](http://hadoopecosystemtable.github.io/) & [big-data](http://blog.andreamostosi.name/big-data/).

Your contributions are always welcome!

- [Awesome Big Data](#awesome-bigdata)
    - [Frameworks](#frameworks)
    - [Distributed Programming](#distributed-programming)
    - [Distributed Filesystem](#distributed-filesystem)
    - [Key-Map Data Model](#key-map-data-model)
    - [Document Data Model](#document-data-model)
    - [Key-value Data Model](#key-value-data-model)
    - [Graph Data Model](#graph-data-model)
    - [NewSQL Databases](#newsql-databases)
    - [Columnar Databases](#columnar-databases)
    - [Time-Series Databases](#time-series-databases)
    - [SQL-like processing](#sql-like-processing)
    - [Integrated Development Environments](#integrated-development-environments)
    - [Data Ingestion](#data-ingestion)
    - [Message-oriented middleware](#message-oriented-middleware)
    - [Service Programming](#service-programming)
    - [Scheduling](#scheduling)
    - [Machine Learning](#machine-learning)
    - [Benchmarking](#benchmarking)
    - [Security](#security)
    - [System Deployment](#system-deployment)
    - [Container Manager](#container-manager)
    - [Applications](#applications)
    - [Search engine and framework](#search-engine-and-framework)
    - [MySQL forks and evolutions](#mysql-forks-and-evolutions)
    - [PostgreSQL forks and evolutions](#postgresql-forks-and-evolutions)
    - [Memcached forks and evolutions](#memcached-forks-and-evolutions)
    - [Embedded Databases](#embedded-databases)
    - [Business Intelligence](#business-intelligence)
    - [Data Analysis](#data-analysis)
    - [Data Warehouse](#data-warehouse)
    - [Data Visualization](#data-visualization)
    - [Internet of Things](#internet-of-things)

- [Other Awesome Lists](#other-awesome-lists)


## Frameworks

* [Apache Hadoop](http://hadoop.apache.org/) - framework for distributed processing. Integrates MapReduce (parallel processing), YARN (job scheduling) and HDFS (distributed file system).

## Distributed Programming

* [AddThis Hydra](https://github.com/addthis/hydra) - distributed data processing and storage system originally developed at AddThis.
* [Akela](https://github.com/mozilla-metrics/akela) - Mozilla's utility library for Hadoop, HBase, Pig, etc..
* [Amazon Lambda](http://aws.amazon.com/lambda/) - a compute service that runs your code in response to events and automatically manages the compute resources for you.
* [AMPLab SIMR](http://databricks.github.io/simr/) - run Spark on Hadoop MapReduce v1.
* [AMPLab Succinct](http://succinct.cs.berkeley.edu/wp/wordpress/) - Enabling Queries on Compressed Data.
* [Apache Crunch](http://crunch.apache.org/) - a simple Java API for tasks like joining and data aggregation that are tedious to implement on plain MapReduce.
* [Apache DataFu](http://incubator.apache.org/projects/datafu.html) - collection of user-defined functions for Hadoop and Pig developed by LinkedIn.
* [Apache Flink](http://flink.incubator.apache.org/) - high-performance runtime, and automatic program optimization.
* [Apache Gora](http://gora.apache.org/) - framework for in-memory data model and persistence.
* [Apache Hama](http://hama.apache.org/) - BSP (Bulk Synchronous Parallel) computing framework.
* [Apache MapReduce](http://wiki.apache.org/hadoop/MapReduce/) - programming model for processing large data sets with a parallel, distributed algorithm on a cluster.
* [Apache Pig](https://pig.apache.org/) - high level language to express data analysis programs for Hadoop.
* [Apache S4](http://incubator.apache.org/s4/) - framework for stream processing, implementation of S4.
* [Apache Spark](http://spark.incubator.apache.org/) - framework for in-memory cluster computing.
* [Apache Spark Streaming](http://spark.incubator.apache.org/docs/0.7.3/streaming-programming-guide.html) - framework for stream processing, part of Spark.
* [Apache Storm](http://storm-project.net/) - framework for stream processing by Twitter also on YARN.
* [Apache Tez](http://tez.incubator.apache.org/) - application framework for executing a complex DAG (directed acyclic graph) of tasks, built on YARN.
* [Apache Twill](https://incubator.apache.org/projects/twill.html) - abstraction over YARN that reduces the complexity of developing distributed applications.
* [Cascalog](http://cascalog.org/) - data processing and querying library.
* [Cheetah](http://vldbarc.org/pvldb/vldb2010/pvldb_vol3/I08.pdf) - High Performance, Custom Data Warehouse on Top of MapReduce.
* [Concurrent Cascading](http://www.cascading.org/) - framework for data management/analytics on Hadoop.
* [Damballa Parkour](https://github.com/damballa/parkour) - MapReduce library for Clojure.
* [Datasalt Pangool](https://github.com/datasalt/pangool) - alternative MapReduce paradigm.
* [DataTorrent StrAM](https://www.datatorrent.com/) - real-time engine is designed to enable distributed, asynchronous, real time in-memory big-data computations in as unblocked a way as possible, with minimal overhead and impact on performance.
* [DistributedR](http://www.vertica.com/distributedr/) - scalable high-performance platform for the R language.
* [Drools](http://www.drools.org/) - a Business Rules Management System (BRMS) solution.
* [eBay Oink](https://github.com/eBay/oink) - REST based interface for PIG execution.
* [Esper](http://esper.codehaus.org/) - a highly scalable, memory-efficient, in-memory computing, SQL-standard, minimal latency, real-time streaming-capable Big Data processing engine for historical data.
* [Facebook Corona](https://www.facebook.com/notes/facebook-engineering/under-the-hood-scheduling-mapreduce-jobs-more-efficiently-with-corona/10151142560538920) - Hadoop enhancement which removes single point of failure.
* [Facebook Peregrine](http://peregrine_mapreduce.bitbucket.org/) - Map Reduce framework.
* [Facebook Scuba](https://www.facebook.com/notes/facebook-engineering/under-the-hood-data-diving-with-scuba/10150599692628920) - distributed in-memory datastore.
* [GearPump](https://github.com/intel-hadoop/gearpump) - a lightweight real-time big data streaming engine.
* [Geotrellis](http://geotrellis.io/) - geographic data processing engine for high performance applications.
* [GetStream Stream Framework](https://github.com/tschellenbach/Stream-Framework) - a Python library, which allows you to build newsfeed and notification systems using Cassandra and/or Redis.
* [GIS Tools for Hadoop](http://esri.github.io/gis-tools-for-hadoop/) - Big Data Spatial Analytics for the Hadoop Framework.
* [Google Dataflow](http://googledevelopers.blogspot.it/2014/06/cloud-platform-at-google-io-new-big.html) - create data pipelines to help themæingest, transform and analyze data.
* [Google MapReduce](http://research.google.com/archive/mapreduce.html) - map reduce framework.
* [Google MillWheel](http://research.google.com/pubs/pub41378.html) - fault tolerant stream processing framework.
* [GraphLab Dato](https://dato.com/products/create/open_source.html) - fast, scalable engine of GraphLab Create, a Python library.
* [Hazelcast](http://hazelcast.com/products/hazelcast/) - In-Memory Data Grid.
* [HParser](http://www.informatica.com/us/products/big-data/hparser/) - data parsing transformation environment optimized for Hadoop.
* [IBM Streams](http://www.ibm.com/software/products/en/infosphere-streams) - advanced analytic platform that allows user-developed applications to quickly ingest, analyze and correlate information as it arrives from thousands of real-time sources.
* [JAQL](https://code.google.com/p/jaql/) - declarative programming language for working with structured, semi-structured and unstructured data.
* [Kite](http://kitesdk.org/docs/current/) - is a set of libraries, tools, examples, and documentation focused on making it easier to build systems on top of the Hadoop ecosystem.
* [Kryo](https://github.com/EsotericSoftware/kryo) - Java serialization and cloning: fast, efficient, automatic.
* [LinkedIn Cubert](https://github.com/linkedin/Cubert) - a fast and efficient batch computation engine for complex analysis and reporting of massive datasets on Hadoop.
* [Lipstick](https://github.com/Netflix/Lipstick) - Pig workflow visualization tool.
* [Metamarkers Druid](http://druid.io/) - framework for real-time analysis of large datasets.
* [Microsoft Azure Stream Analytics](http://azure.microsoft.com/en-us/services/stream-analytics/) - an event processing engine that helps uncover real-time insights from devices, sensors, infrastructure, applications and data.
* [Microsoft Orleans](http://research.microsoft.com/en-us/projects/orleans/) - a straightforward approach to building distributed high-scale computing applications.
* [Microsoft Trill](http://research.microsoft.com/en-us/projects/trill/) - a high-performance in-memory incremental analytics engine.
* [Netflix Aegisthus](https://github.com/Netflix/aegisthus) - Bulk Data Pipeline out of Cassandra. implements a reader for the SSTable format and provides a map/reduce program to create a compacted snapshot of the data contained in a column family.
* [Netflix Lipstick](https://github.com/Netflix/Lipstick) - Pig Visualization framework.
* [Netflix Mantis](http://qconsf.com/presentation/mantis-netflixs-event-stream-processing-system) - Event Stream Processing System.
* [Netflix PigPen](https://github.com/Netflix/PigPen) - map-reduce for Clojure whiche compiles to Apache Pig.
* [Netflix STAASH](https://github.com/Netflix/staash) - language-agnostic as well as storage-agnostic web interface for storing data into persistent storage systems.
* [Netflix Surus](https://github.com/Netflix/Surus) - a collection of tools for analysis in Pig and Hive.
* [Netflix Zeno](https://github.com/Netflix/zeno) - Netflix's In-Memory Data Propagation Framework.
* [Nextflow](http://www.nextflow.io) - Dataflow oriented toolkit for parallel and distributed computational pipelines.
* [Nokia Disco](http://discoproject.org/) - MapReduce framework developed by Nokia.
* [Parsely Streamparse](https://github.com/Parsely/streamparse) - streamparse lets you run Python code against real-time streams of data. It also integrates Python smoothly with Apache Storm..
* [PigPen](https://github.com/Netflix/PigPen) - PigPen is map-reduce for Clojure, or distributed Clojure. It compiles to Apache Pig, but you don't need to know much about Pig to use it.
* [Pinterest Pinlater](http://engineering.pinterest.com/post/91288882494/pinlater-an-asynchronous-job-execution-system) - asynchronous job execution system.
* [Pubnub](http://www.pubnub.com/) - Data stream network.
* [Pydoop](http://pydoop.sourceforge.net/docs/) - Python MapReduce and HDFS API for Hadoop.
* [ScaleOut hServer](http://www.scaleoutsoftware.com/) - fast, scalable in-memory data grid for Hadoop.
* [SeqPig](http://seqpig.sourceforge.net/) - Simple and scalable scripting for large sequencing data set(ex: bioinfomation) in Hadoop .
* [SigmoidAnalytics Spork](https://github.com/sigmoidanalytics/spork) - Pig on Apache Spark.
* [SNAP](https://github.com/snap-stanford/snap) - Stanford Network Analysis Platform is a general purpose, high performance system for analysis and manipulation of large networks.
* [spark-dataflow](https://github.com/cloudera/spark-dataflow) - allows users to execute dataflow pipelines with Spark.
* [SpatialHadoop](http://spatialhadoop.cs.umn.edu/) - SpatialHadoop is a MapReduce extension to Apache Hadoop designed specially to work with spatial data. .
* [Spring for Apache Hadoop](http://projects.spring.io/spring-hadoop/) - unified configuration model and easy to use APIs for using HDFS, MapReduce, Pig, and Hive.
* [SQLStream Blaze](http://www.sqlstream.com/blaze/) - stream processing platform.
* [Stratio Streaming](http://www.openstratio.org/about/stratio-streaming/) - the union of a real-time messaging bus with a complex event processing engine using Spark Streaming.
* [Stratosphere](http://stratosphere.eu/) - general purpose cluster computing framework.
* [Streamdrill](https://streamdrill.com/) - usefull for counting activities of event streams over different time windows and finding the most active one.
* [Sumo Logic](http://www.sumologic.com/) - cloud based analyzer for machine-generated data..
* [Teradata QueryGrid](http://it.teradata.com/Teradata-QueryGrid/) - data-access layer that can orchestrate multiple modes of analysis across multiple databases plus Hadoop.
* [TIBCO ActiveSpaces](http://www.tibco.com/products/automation/in-memory-computing/in-memory-data-grid/activespaces-enterprise-edition) - in-memory data grid.
* [Tigon](http://cask.co/products/tigon/) - a distributed framework built on Apache HadoopTM and Apache HBaseTM for real-time, high-throughput, low-latency data processing and analytics applications.
* [Torch](http://torch.ch/) - Scientific computing for LuaJIT.
* [Trident](https://storm.apache.org/documentation/Trident-tutorial.html) - a high-level abstraction for doing realtime computing on top of Storm.
* [Twitter Scalding](https://github.com/twitter/scalding) - Scala library for Map Reduce jobs, built on Cascading.
* [Twitter Summingbird](https://github.com/twitter/summingbird) - Streaming MapReduce with Scalding and Storm, by Twitter.
* [Twitter TSAR](https://blog.twitter.com/2014/tsar-a-timeseries-aggregator) - TimeSeries AggregatoR by Twitter.

## Distributed Filesystem

* [Apache HDFS](http://hadoop.apache.org/) - a way to store large files across multiple machines.
* [BeeGFS](http://www.fhgfs.com/cms/) - formerly FhGFS, parallel distributed file system.
* [Ceph Filesystem](http://ceph.com/ceph-storage/file-system/) - software storage platform designed.
* [Disco DDFS](http://disco.readthedocs.org/en/latest/howto/ddfs.html) - distributed filesystem.
* [Facebook Haystack](https://www.facebook.com/note.php?note_id=76191543919) - object storage system.
* [Google Colossus](https://google.com/) - distributed filesystem (GFS2).
* [Google GFS](https://google.com/) - distributed filesystem.
* [Google Megastore](http://research.google.com/pubs/pub36971.html) - scalable, highly available storage.
* [GridGain](http://www.gridgain.org/) - GGFS, Hadoop compliant in-memory file system.
* [HDSF-DU](https://github.com/twitter/hdfs-du) - HDFS-DU is an interactive visualization of the Hadoop distributed file system. .
* [Lustre file system](http://wiki.lustre.org/) - high-performance distributed filesystem.
* [Netflix S3mper](https://github.com/Netflix/s3mper) - library that provides an additional layer of consistency checking on top of Amazon's S3 index through use of a consistent, secondary index.
* [Quantcast File System QFS](https://www.quantcast.com/engineering/qfs/) - open-source distributed file system.
* [Red Hat GlusterFS](http://www.gluster.org/) - scale-out network-attached storage file system.
* [Tachyon](http://tachyon-project.org/) - reliable file sharing at memory speed across cluster frameworks.

## Key-Map Data Model

* [Actian Vector](http://www.actian.com/) - column-oriented analytic database.
* [Apache Accumulo](http://accumulo.apache.org/) - distribuited key/value store, built on Hadoop.
* [Apache Cassandra](http://cassandra.apache.org/) - column-oriented distribuited datastore, inspired by BigTable.
* [Apache HBase](http://hbase.apache.org/) - column-oriented distribuited datastore, inspired by BigTable.
* [Facebook HydraBase](https://code.facebook.com/posts/321111638043166/hydrabase-the-evolution-of-hbase-facebook/) - evolution of HBase made by Facebook.
* [Google BigTable](http://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en//archive/bigtable-osdi06.pdf) - column-oriented distributed datastore.
* [Google Cloud Datastore](https://developers.google.com/datastore/) - is a fully managed, schemaless database for storing non-relational data over BigTable.
* [Hypertable](http://hypertable.org/) - column-oriented distribuited datastore, inspired by BigTable.
* [InfiniDB](http://infinidb.co/) - is accessed through a MySQL interface and use massive parallel processing to parallelize queries.
* [MapR-DB](http://content.dataversity.net/rs/wilshireconferences/images/MapR-DB_Product_Preview_for_NoSQL_Now.pdf) - fast, scalable, and enterprise-ready in-Hadoop database architected to manage big data.
* [Netflix Priam](https://github.com/Netflix/Priam) - Co-Process for backup/recovery, Token Management, and Centralized Configuration management for Cassandra.
* [OhmData C5](http://ohmdata.com/) - improved version of HBase.
* [Sqrrl](http://sqrrl.com/product/sqrrl-enterprise/) - NoSQL databases on top of Apache Accumulo.
* [Tephra](https://github.com/continuuity/tephra) - Transactions for HBase.
* [Twitter Manhattan](https://blog.twitter.com/2014/manhattan-our-real-time-multi-tenant-distributed-database-for-twitter-scale) - real-time, multi-tenant distributed database for Twitter scale.

## Document Data Model

* [Actian Versant](http://www.actian.com/products/operational-databases/) - commercial object-oriented database management systems .
* [Amazon SimpleDB](http://aws.amazon.com/simpledb/) - a highly available and flexible non-relational data store that offloads the work of database administration.
* [Clusterpoint](http://www.clusterpoint.com/) - a database software for high-speed storage and large-scale processing of XML and JSON data on clusters of commodity hardware.
* [Crate Data](https://crate.io/) - is an open source massively scalable data store. It requires zero administration.
* [Facebook Apollo](http://www.infoq.com/news/2014/06/facebook-apollo) - Facebook’s Paxos-like NoSQL database.
* [jumboDB](http://comsysto.github.io/jumbodb/) - document oriented datastore over Hadoop.
* [LinkedIn Espresso](http://data.linkedin.com/projects/espresso) - horizontally scalable document-oriented NoSQL data store.
* [MarkLogic](http://www.marklogic.com/) - Schema-agnostic Enterprise NoSQL database technology.
* [Microsoft DocumentDB](http://azure.microsoft.com/en-us/services/documentdb/) - fully-managed, highly-scalable, NoSQL document database service.
* [MongoDB](http://www.mongodb.org/) - Document-oriented database system.
* [RavenDB](http://www.ravendb.net/) - A transactional, open-source Document Database.
* [RethinkDB](http://www.rethinkdb.com/) - document database that supports queries like table joins and group by.
* [Terrastore](https://code.google.com/p/terrastore/) - a modern document store which provides advanced scalability and elasticity features without sacrificing consistency.
* [TokuMX](http://www.tokutek.com/products/tokumx-for-mongodb/) - High-Performance MongoDB Distribution.

## Key-value Data Model

* [Aerospike](http://www.aerospike.com/) - NoSQL flash-optimized, in-memory. Open source and "Server code in 'C' (not Java or Erlang) precisely tuned to avoid context switching and memory copies..
* [Amazon DynamoDB](http://aws.amazon.com/dynamodb/) - distributed key/value store, implementation of Dynamo paper.
* [Couchbase ForestDB](https://github.com/couchbaselabs/forestdb) - Fast Key-Value Storage Engine Based on Hierarchical B+-Tree Trie.
* [Edis](http://inaka.github.io/edis/) - is a protocol-compatible Server replacement for Redis.
* [ElephantDB](https://github.com/nathanmarz/elephantdb) - Distributed database specialized in exporting data from Hadoop.
* [EventStore](http://geteventstore.com) - distributed time series database.
* [Exasolution](http://www.exasol.com/en/products/exasolution/) - an in-memory, column-oriented, relational database management system.
* [HyperDex](http://hyperdex.org/) - next generation key-value store.
* [KAI](http://sourceforge.net/projects/kai/) - a distributed key-value datastore.
* [LinkedIn Krati](https://github.com/linkedin-sna/sna-page/tree/master/krati) - is a simple persistent data store with very low latency and high throughput.
* [Linkedin Voldemort](http://www.project-voldemort.com/voldemort/) - distributed key/value storage system.
* [MemcacheDB](http://memcachedb.org/) - a distributed key-value storage system designed for persistent.
* [Netflix Dynomite](http://techblog.netflix.com/2014/03/netflixoss-season-2-episode-1.html) - thin Dynamo-based replication for cached data.
* [Oracle NoSQL Database](http://www.oracle.com/technetwork/database/database-technologies/nosqldb/overview/index.html) - distributed key-value database by Oracle Corporation.
* [RAMCloud](https://ramcloud.atlassian.net/wiki/display/RAM/RAMCloud) - storage system that provides large-scale low-latency storage by keeping all data in DRAM all the time and aggregating the main memories of thousands of servers.
* [Redis](http://redis.io) - in memory key value datastore.
* [Redis Cluster](http://redis.io/topics/cluster-spec) - distributed implementation of Redis.
* [Redis Sentinel](http://redis.io/topics/sentinel) - system designed to help managing Redis instances.
* [Riak](https://github.com/basho/riak) - a decentralized datastore.
* [Scalaris](https://code.google.com/p/scalaris/) - a distributed transactional key-value store.
* [Storehaus](https://github.com/twitter/storehaus) - library to work with asynchronous key value stores, by Twitter.
* [Tarantool](https://github.com/tarantool/tarantool) - an efficient NoSQL database and a Lua application server.
* [TreodeDB](https://github.com/Treode/store) - key-value store that's replicated and sharded and provides atomic multirow writes.
* [Yahoo Sherpa](http://en.wikipedia.org/wiki/Yahoo_Sherpa) - hosted, distributed and geographically replicated key-valueÊcloud storage platform.

## Graph Data Model

* [Apache Giraph](http://giraph.apache.org/) - implementation of Pregel, based on Hadoop.
* [Apache Spark Bagel](http://spark.incubator.apache.org/docs/0.7.3/bagel-programming-guide.html) - implementation of Pregel, part of Spark.
* [ArangoDB](https://www.arangodb.org/) - multi model distribuited database.
* [Facebook TAO](https://www.facebook.com/notes/facebook-engineering/tao-the-power-of-the-graph/10151525983993920) - TAO is the distributed data store that is widely used at facebook to store and serve the social graph.
* [Faunus](http://thinkaurelius.github.io/faunus/) - Hadoop-based graph analytics engine for analyzing graphs represented across a multi-machine compute cluster.
* [Google Cayley](https://github.com/google/cayley) - open-source graph database.
* [Google Pregel](http://kowshik.github.io/JPregel/pregel_paper.pdf) - graph processing framework.
* [GraphLab PowerGraph](http://graphlab.org/projects/source.html) - a core C++ GraphLab API and a collection of high-performance machine learning and data mining toolkits built on top of the GraphLab API.
* [GraphX](https://amplab.cs.berkeley.edu/publication/graphx-grades/) - resilient Distributed Graph System on Spark.
* [Gremlin](https://github.com/tinkerpop/gremlin) - graph traversal Language.
* [HyperGraphDB](http://www.hypergraphdb.org/) - general purpose, open-source data storage mechanism based on a powerful knowledge management formalism known as directed hypergraphs.
* [InfiniteGraph](http://www.objectivity.com/infinitegraph) - distributed graph database.
* [Infovore](https://github.com/paulhoule/infovore) - RDF-centric Map/Reduce framework.
* [Intel GraphBuilder](https://01.org/graphbuilder/) - tools to construct large-scale graphs on top of Hadoop.
* [MapGraph](http://mapgraph.io/) - Massively Parallel Graph processing on GPUs.
* [Neo4j](http://www.neo4j.org/) - graph database writting entirely in Java.
* [OrientDB](http://www.orientechnologies.com/) - document and graph database.
* [Phoebus](https://github.com/xslogic/phoebus) - framework for large scale graph processing.
* [Pinterest Zen](https://www.youtube.com/watch?v=yI0vHfgK6oI) - Pinterest's Graph Storage Service.
* [Sparksee](http://www.sparsity-technologies.com/) - scalable high-performance graph database.
* [Stardog](http://stardog.com/) - graph database: search, query, reasoning, and constraints in a lightweight, pure Java system.
* [Titan](http://thinkaurelius.github.io/titan/) - distributed graph database, built over Cassandra.
* [Twitter FlockDB](https://github.com/twitter/flockdb) - distribuited graph database.

## NewSQL Databases

* [Actian Ingres](http://www.actian.com/products/operational-databases/) - commercially supported, open-source SQL relational database management system.
* [BayesDB](http://probcomp.csail.mit.edu/bayesdb/index.html) - statistic oriented SQL database.
* [Cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [Datomic](http://www.datomic.com/) - distributed database designed to enable scalable, flexible and intelligent applications.
* [FoundationDB](https://foundationdb.com/) - distributed database, inspired by F1.
* [Google F1](http://research.google.com/pubs/pub41344.html) - distributed SQL database built on Spanner.
* [Google Spanner](http://research.google.com/archive/spanner.html) - globally distributed semi-relational database.
* [H-Store](http://hstore.cs.brown.edu/) - is an experimental main-memory, parallel database management system that is optimized for on-line transaction processing (OLTP) applications.
* [HandlerSocket](http://www.percona.com/doc/percona-server/5.5/performance/handlersocket.html) - NoSQL plugin for MySQL/MariaDB.
* [IBM DB2](http://www.ibm.com/software/data/db2/) - object-relational database management system.
* [InfiniSQL](http://www.infinisql.org/) - infinity scalable RDBMS.
* [MemSQL](http://www.memsql.com/) - in memory SQL database witho optimized columnar storage on flash.
* [NuoDB](http://www.nuodb.com/) - SQL/ACID compliant distributed database.
* [Oracle Database](http://www.oracle.com/us/corporate/features/database-12c/index.html) - object-relational database management system.
* [Oracle TimesTen in-Memory Database](http://www.oracle.com/technetwork/database/database-technologies/timesten/overview/index.html) - in-memory, relational database management system with persistence and recoverability.
* [Pivotal GemFire XD](http://gemfirexd.docs.gopivotal.com/latest/userguide/index.html?q=about_users_guide.html/) - Low-latency, in-memory, distributed SQL data store. Provides SQL interface to in-memory table data, persistable in HDFS.
* [SAP HANA](http://www.saphana.com/welcome) - is an in-memory, column-oriented, relational database management system.
* [Segment SQL](https://segment.com/redshift) - Track your customer data to Amazon Redshift.
* [SenseiDB](http://senseidb.com/) - distributed, realtime, semi-structured database.
* [Sky](http://skydb.io/) - database used for flexible, high performance analysis of behavioral data.
* [SymmetricDS](http://www.symmetricds.org/) - open source software for both file and database synchronization.
* [Teradata Database](http://it.teradata.com/products-and-services/Teradata-Database/) - complete relational database management system.
* [VoltDB](http://voltdb.com/) - in-memory NewSQL database.

## Columnar Databases

* [Amazon RedShift](http://aws.amazon.com/redshift/) - data warehouse service, based on PostgreSQL.
* [C-Store](http://db.lcs.mit.edu/projects/cstore/) - column oriented DBMS.
* [Google BigQuery](http://research.google.com/pubs/pub36632.html) - framework for interactive analysis, implementation of Dremel.
* [Google Dremel](http://research.google.com/pubs/pub36632.html) - framework for interactive analysis, implementation of Dremel.
* [MonetDB](https://www.monetdb.org/) - column store database.
* [Parquet](http://parquet.io/) - columnar storage format for Hadoop.
* [Pivotal Greenplum](https://www.pivotal.io/big-data/pivotal-greenplum-database) - purpose-built, dedicated analytic data warehouse.
* [Vertica](http://www.vertica.com/) - is designed to manage large, fast-growing volumes of data and provide very fast query performance when used for data warehouses.

## Time-Series Databases

* [Cube](http://square.github.io/cube/) - uses MongoDB to store time series data.
* [Etsy StatsD](https://github.com/etsy/statsd/) - simple daemon for easy stats aggregation.
* [InfluxDB](http://influxdb.com/) - distributed time series database.
* [Kairos](https://pypi.python.org/pypi/kairos) - Time series data storage in Redis, Mongo, SQL and Cassandra.
* [Kairosdb](https://code.google.com/p/kairosdb/) - similar to OpenTSDB but allows for Cassandra.
* [OpenTSDB](http://opentsdb.net) - distributed time series database on top of HBase.
* [Prometheus](http://prometheus.io/) - an open-source service monitoring system and time series database.
* [Square Cube](http://square.github.io/cube/) - system for collecting timestamped events and deriving metrics.
* [TempoIQ](https://tempoiq.com/) - Cloud-based sensor analytics.

## SQL-like processing

* [Actian SQL for Hadoop](http://www.actian.com/products/analytics-platform/) - high performance interactive SQL access to all Hadoop data.
* [AMPLAB Shark](https://github.com/amplab/shark/) - data warehouse system for Spark.
* [Apache Drill](http://incubator.apache.org/drill/) - framework for interactive analysis, inspired by Dremel.
* [Apache HCatalog](http://hive.apache.org/docs/hcat_r0.5.0/) - table and storage management layer for Hadoop.
* [Apache Hive](http://hive.apache.org/) - SQL-like data warehouse system for Hadoop.
* [Apache Optiq](https://wiki.apache.org/incubator/OptiqProposal) - framework that allows efficient translation of queries involving heterogeneous and federated data.
* [Apache Phoenix](http://phoenix.incubator.apache.org/index.html) - SQL skin over HBase.
* [BlinkDB](http://blinkdb.org/) - massively parallel, approximate query engine.
* [Cloudera Impala](http://www.cloudera.com/content/cloudera/en/products-and-services/cdh/impala.html) - framework for interactive analysis, Inspired by Dremel.
* [Concurrent Lingual](http://www.cascading.org/lingual/) - SQL-like query language for Cascading.
* [Datasalt Splout SQL](http://www.datasalt.com/products/splout-sql/) - full SQL query engine for big datasets.
* [eBay Kylin](http://www.kylin.io/) - Distributed Analytics Engine from eBay Inc. that provides SQL interface and multi-dimensional analysis (OLAP) on Hadoop supporting extremely large datasets.
* [Facebook PrestoDB](http://prestodb.io/) - distributed SQL query engine.
* [Hadapt](http://hadapt.com/) - a native implementation of SQL for the Apache Hadoop open-source project.
* [JethroData](http://jethrodata.com/product-2/product/) - index-based SQL engine for Hadoop.
* [Metanautix Quest](https://metanautix.com/product/) - data compute engine.
* [Pivotal HAWQ](http://www.gopivotal.com/pivotal-products/data/pivotal-hd) - SQL-like data warehouse system for Hadoop.
* [RainstorDB](http://rainstor.com/products/rainstor-database/) - database for storing petabyte-scale volumes of structured and semi-structured data.
* [Spark Catalyst](https://github.com/apache/spark/tree/master/sql) - is a Query Optimization Framework for Spark and Shark.
* [SparkSQL](http://databricks.com/blog/2014/03/26/Spark-SQL-manipulating-structured-data-using-Spark.html) - Manipulating Structured Data Using Spark.
* [Splice Machine](http://www.splicemachine.com/) - a full-featured SQL-on-Hadoop RDBMS with ACID transactions.
* [Stinger](http://hortonworks.com/labs/stinger/) - interactive query for Hive.
* [Tajo](http://tajo.incubator.apache.org/) - distributed data warehouse system on Hadoop.
* [Trafodion](https://wiki.trafodion.org/wiki/index.php/Main_Page) - enterprise-class SQL-on-HBase solution targeting big data transactional or operational workloads.

## Integrated Development Environments

* [R-Studio](https://github.com/rstudio/rstudio) - IDE for R.

## Data Ingestion

* [Amazon Kinesis](http://aws.amazon.com/kinesis/) - real-time processing of streaming data at massive scale.
* [Apache BookKeeper](http://zookeeper.apache.org/bookkeeper/) - a distributed logging service called BookKeeper and a distributed publish/subscribe system built on top of BookKeeper called Hedwig.
* [Apache Chukwa](http://incubator.apache.org/chukwa/) - data collection system.
* [Apache Flume](http://flume.apache.org/) - service to manage large amount of log data.
* [Apache Samza](http://samza.incubator.apache.org/) - stream processing framework, based on Kafla and YARN.
* [Apache Sqoop](http://sqoop.apache.org/) - tool to transfer data between Hadoop and a structured datastore.
* [Apache UIMA](https://uima.apache.org/) - Unstructured Information Management applications are software systems that analyze large volumes of unstructured information in order to discover knowledge that is relevant to an end user.
* [Cloudera Morphlines](https://github.com/cloudera/cdk/tree/master/cdk-morphlines) - framework that help ETL to Solr, HBase and HDFS.
* [Facebook Scribe](https://github.com/facebook/scribe) - streamed log data aggregator.
* [Fluentd](http://fluentd.org/) - tool to collect events and logs.
* [Google Photon](http://research.google.com/pubs/pub41318.html) - geographically distributed system for joining multiple continuously flowing streams of data in real-time with high scalability and low latency.
* [Heka](https://github.com/mozilla-services/heka) - open source stream processing software system.
* [HIHO](https://github.com/sonalgoyal/hiho) - framework for connecting disparate data sources with Hadoop.
* [LinkedIn Camus](https://github.com/linkedin/camus) - Kafka to HDFS pipeline. It is a mapreduce job that does distributed data loads out of Kafka.
* [LinkedIn Databus](http://data.linkedin.com/projects/databus) - stream of change capture events for a database.
* [LinkedIn Gobblin](http://engineering.linkedin.com/data-ingestion/gobblin-big-data-ease) - a framework for Solving Big Data Ingestion Problem.
* [LinkedIn Kamikaze](https://github.com/linkedin/kamikaze) - utility package for compressing sorted integer arrays.
* [Linkedin Lumos](http://www.slideshare.net/Hadoop_Summit/th-220p230-cramachandranv1) - bridge from OLTP to OLAP for use it on Hadoop.
* [LinkedIn White Elephant](https://github.com/linkedin/white-elephant) - log aggregator and dashboard.
* [Logstash](http://logstash.net) - a tool for managing events and logs.
* [Netflix Ribbon](https://github.com/Netflix/ribbon) - a Inter Process Communication (remote procedure calls) library with built in software load balancers. The primary usage model involves REST calls with various serialization scheme support.
* [Netflix Suro](https://github.com/Netflix/suro) - data pipeline service for collecting, aggregating, and dispatching large volume of application events including log data based on Chukwa.
* [Pinterest Secor](https://github.com/pinterest/secor) - is a service implementing Kafka log persistance.
* [Record Breaker](http://cloudera.github.io/RecordBreaker/) - Automatic structure for your text-formatted data.
* [TIBCO Enterprise Message Service](http://www.tibco.com/products/automation/enterprise-messaging/enterprise-message-service) - standards-based messaging middleware.
* [Twitter Zipkin](https://github.com/twitter/zipkin) - distributed tracing system that helps us gather timing data for all the disparate services at Twitter.
* [Vibe Data Stream](http://www.informatica.com/us/products/big-data/vibe-data-stream/) - streaming data collection for real-time Big Data analytics.

## Message-oriented middleware

* [ActiveMQ](http://activemq.apache.org/) - open source messaging and Integration Patterns server.
* [Amazon Simple Queue Service](http://aws.amazon.com/sqs/) - fast, reliable, scalable, fully managed queue service.
* [Apache Kafka](http://kafka.apache.org/) - distributed publish-subscribe messaging system.
* [Apache Qpid](http://qpid.apache.org/) - messaging tools that speak AMQP and support many languages and platforms.
* [Apollo](http://activemq.apache.org/apollo/) - ActiveMQ's next generation of messaging.
* [Beanstalkd](http://kr.github.io/beanstalkd/) - simple, fast work queue.
* [Bit.ly NSQ](http://nsq.io/) - realtime distributed message processing at scale.
* [Celery](http://www.celeryproject.org/) - Distributed Task Queue.
* [Crossroads I/O](http://www.crossroads.io/) - library for building scalable and high performance distributed applications.
* [Darner](https://github.com/wavii/darner) - simple, lightweight message queue.
* [Facebook Iris](https://code.facebook.com/posts/820258981365363/building-mobile-first-infrastructure-for-messenger/) - a totally ordered queue of messaging updates with separate pointers into the queue indicating the last update sent to your Messenger app and the traditional storage tier.
* [Gearman](http://gearman.org) - Job Server.
* [Google Cloud Pub/Sub](https://cloud.google.com/pubsub/) - reliable, many-to-many, asynchronous messaging hosted on Google's infrastructure.
* [HornetQ](http://www.jboss.org/hornetq) - open source project to build a multi-protocol, embeddable, very high performance, clustered, asynchronous messaging system.
* [IronMQ](http://www.iron.io/mq) - easy-to-use highly available message queuing service.
* [Kestrel](http://robey.github.io/kestrel/) - distributed message queue system.
* [Marconi](https://wiki.openstack.org/wiki/Marconi) - queuing and notification service made by and for OpenStack, but not only for it.
* [RabbitMQ](http://www.rabbitmq.com/) - Robust messaging for applications.
* [RestMQ](http://restmq.com/) - message queue which uses HTTP as transport, JSON to format a minimalist protocol and is organized as REST resources.
* [RQ](http://python-rq.org/) - simple Python library for queueing jobs and processing them in the background with workers.
* [Sidekiq](http://sidekiq.org/) - Simple, efficient background processing for Ruby.
* [ZeroMQ](http://www.zeromq.org/) - The Intelligent Transport Layer.

## Service Programming

* [Akka Toolkit](http://akka.io/) - runtime for distributed, and fault tolerant event-driven applications on the JVM.
* [Apache Avro](http://avro.apache.org/) - data serialization system.
* [Apache Curator](http://curator.apache.org/) - Java libaries for Apache ZooKeeper.
* [Apache Karaf](http://karaf.apache.org/) - OSGi runtime that runs on top of any OSGi framework.
* [Apache Thrift](http://thrift.apache.org//) - framework to build binary protocols.
* [Apache Zookeeper](http://zookeeper.apache.org/) - centralized service for process management.
* [Google Chubby](http://research.google.com/archive/chubby.html) - a lock service for loosely-coupled distributed systems.
* [Linkedin Norbert](http://data.linkedin.com/opensource/norbert) - cluster manager.
* [MPICH](http://www.mpich.org/) - high performance and widely portable implementation of the Message Passing Interface (MPI) standard.
* [OpenMPI](http://www.open-mpi.org/) - message passing framework.
* [Serf](http://www.serfdom.io/) - decentralized solution for service discovery and orchestration.
* [Spotify Luigi](https://github.com/spotify/luigi) - a Python package for building complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization, handling failures, command line integration, and much more.
* [Spring XD](https://github.com/spring-projects/spring-xd) - distributed and extensible system for data ingestion, real time analytics, batch processing, and data export.
* [Twitter Elephant Bird](https://github.com/kevinweil/elephant-bird) - libraries for working with LZOP-compressed data.
* [Twitter Finagle](https://twitter.github.io/finagle/) - asynchronous network stack for the JVM.

## Scheduling

* [Apache Aurora](http://aurora.incubator.apache.org/) - is a service scheduler that runs on top of Apache Mesos.
* [Apache Falcon](http://falcon.incubator.apache.org/) - data management framework.
* [Apache Oozie](http://oozie.apache.org/) - workflow job scheduler.
* [Chronos](http://airbnb.github.io/chronos/) - distributed and fault-tolerant scheduler.
* [Linkedin Azkaban](http://azkaban.github.io/azkaban2/) - batch workflow job scheduler.
* [Pinterest Pinball](http://engineering.pinterest.com/post/74429563460/pinball-building-workflow-management) - customizable platform for creating workflow managers.
* [Sparrow](https://github.com/radlab/sparrow) - scheduling platform.

## Machine Learning

* [Apache Mahout](http://mahout.apache.org/) - machine learning library for Hadoop.
* [Ayasdi Core](http://www.ayasdi.com/) - tool for topological data analysis.
* [brain](https://github.com/harthur/brain) - Neural networks in JavaScript.
* [Cloudera Oryx](https://github.com/cloudera/oryx) - real-time large-scale machine learning.
* [Concurrent Pattern](http://www.cascading.org/pattern/) - machine learning library for Cascading.
* [convnetjs](https://github.com/karpathy/convnetjs) - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [cuDNN](http://devblogs.nvidia.com/parallelforall/accelerate-machine-learning-cudnn-deep-neural-network-library/) - GPU-accelerated library of primitives for deep neural networks.
* [Decider](https://github.com/danielsdeleo/Decider) - Flexible and Extensible Machine Learning in Ruby.
* [etcML](http://www.etcml.com/) - text classification with machine learning.
* [Etsy Conjecture](https://github.com/etsy/Conjecture) - scalable Machine Learning in Scalding.
* [fbcunn](https://github.com/facebook/fbcunn) - Deep Learning CUDA Extensions from Facebook AI Research.
* [Google Sibyl](http://users.soe.ucsc.edu/~niejiazhong/slides/chandra.pdf) - System for Large Scale Machine Learning at Google.
* [H2O](http://0xdata.github.io/h2o/) - statistical, machine learning and math runtime for Hadoop.
* [IBM Watson](http://www.ibm.com/smarterplanet/us/en/ibmwatson/) - cognitive computing system.
* [LinkedIn ml-ease](https://github.com/linkedin/ml-ease) - ADMM based large scale logistic regression.
* [Microsoft Azure Machine Learning](https://studio.azureml.net/) - is built on the machine learning capabilities already available in several Microsoft products including Xbox and Bing and using predefined templates and workflows.
* [MLbase](http://www.mlbase.org/) - distributed machine learning libraries for the BDAS stack.
* [MLPNeuralNet](https://github.com/nikolaypavlov/MLPNeuralNet) - Fast multilayer perceptron neural network library for iOS and Mac OS X.
* [nupic](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing: a brain-inspired machine intelligence platform, and biologically accurate neural network based on cortical learning algorithms.
* [PredictionIO](http://prediction.io/) - machine learning server buit on Hadoop, Mahout and Cascading.
* [scikit-learn](https://github.com/scikit-learn/scikit-learn) - scikit-learn: machine learning in Python.
* [Spark MLlib](http://spark.apache.org/docs/0.9.0/mllib-guide.html) - a Spark implementation of some common machine learning (ML) functionality.
* [Sparkling Water](http://databricks.com/blog/2014/06/30/sparkling-water-h20-spark.html) - combine H2OÕs Machine Learning capabilities with the power of the Spark platform.
* [Theano](http://deeplearning.net/software/theano/) - Python package for deep learning that can utilize NVIDIA's CUDA toolkit to run on the GPU.
* [Thunder](http://thefreemanlab.com/thunder/) - Large-scale analysis of neural data.
* [Vahara](https://github.com/Ganglion/varaha) - Machine learning and natural language processing with Apache Pig.
* [Viv](http://viv.ai/) - global platform that enables developers to plug into and create an intelligent, conversational interface to anything.
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/wiki) - learning system sponsored by Microsoft and Yahoo!.
* [WEKA](http://www.cs.waikato.ac.nz/ml/weka/) - suite of machine learning software.
* [Wit](https://wit.ai/) - Natural Language for the Internet of Things.
* [Wolfram Alpha](http://www.wolframalpha.com/) - computational knowledge engine.
* [YHat ScienceOps](https://yhathq.com/products/scienceops) - platform for deploying, managing, and scaling predictive models in production applications.

## Benchmarking

* [Apache Hadoop Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-3561) - micro-benchmarks for testing Hadoop performances.
* [Berkeley SWIM Benchmark](https://github.com/SWIMProjectUCB/SWIM/wiki) - real-world big data workload benchmark.
* [Big-Bench](https://github.com/intel-hadoop/Big-Bench) - Big Bench Workload Development.
* [Hive-benchmarks](https://github.com/yhuai/hive-benchmarks) - some benchmarking queries for Apache Hive.
* [Hive-testbench](https://github.com/cartershanklin/hive-testbench) - Testbench for experimenting with Apache Hive at any data scale..
* [Intel HiBench](https://github.com/intel-hadoop/HiBench) - a Hadoop benchmark suite.
* [Mesosaurus](https://github.com/mesosphere/mesosaurus) - Mesos task load simulator framework for (cluster and Mesos) performance analysis.
* [Netflix Inviso](https://hadoopsummit.uservoice.com/forums/242807-hadoop-deployment-operations-track/suggestions/5568461-inviso-maximizing-big-data-performance-at-netflix) - performance focused Big Data tool.
* [PUMA Benchmarking](https://issues.apache.org/jira/browse/MAPREDUCE-5116) - benchmark suite for MapReduce applications.
* [Yahoo Gridmix3](https://developer.yahoo.com/blogs/hadoop/gridmix3-emulating-production-workload-apache-hadoop-450.html) - Hadoop cluster benchmarking from Yahoo engineer team.

## Security

* [Apache Knox Gateway](http://knox.apache.org/) - single point of secure access for Hadoop clusters.
* [Apache Ranger](http://argus.incubator.apache.org/) - framework to enable, monitor and manage comprehensive data security across the Hadoop platform (formerly called Apache Argus).
* [Apache Sentry](http://incubator.apache.org/projects/sentry.html) - security module for data stored in Hadoop.
* [PacketPig](https://github.com/packetloop/packetpig) - Open Source Big Data Security Analytics.
* [Voltage SecureData](http://www.voltage.com/products/securedata-enterprise/) - data protection framework.

## System Deployment

* [Ankush](https://github.com/impetus-opensource/ankush) - A big data cluster management tool that creates and manages clusters of different technologies..
* [Apache Ambari](http://ambari.apache.org/) - operational framework for Hadoop mangement.
* [Apache Bigtop](http://bigtop.apache.org//) - system deployment framework for the Hadoop ecosystem.
* [Apache Helix](http://helix.apache.org/) - cluster management framework.
* [Apache Mesos](http://mesos.apache.org/) - cluster manager.
* [Apache Slider](https://github.com/hortonworks/slider) - is a YARN application to deploy existing distributed applications on YARN.
* [Apache Whirr](http://whirr.apache.org/) - set of libraries for running cloud services.
* [Apache YARN](http://hortonworks.com/hadoop/yarn/) - Cluster manager.
* [Brooklyn](http://brooklyncentral.github.io/) - library that simplifies application deployment and management.
* [Buildoop](http://buildoop.github.io/) - Similar to Apache BigTop based on Groovy language.
* [Cloudera Director](http://www.cloudera.com/content/cloudera/en/products-and-services/director.html) - a comprehensive data management platform with the flexibility and power to evolve with your business.
* [Cloudera HUE](http://gethue.com/) - web application for interacting with Hadoop.
* [CloudPhysics](https://www.cloudphysics.com/product/) - collect operational metadata from your virtualized infrastructure, then correlate and analyze it to expose operational hazards and waste that pose a threat to your datacenter performance, efficiency and uptime.
* [Deimos](https://github.com/mesosphere/deimos) - Mesos containerizer hooks for Docker.
* [Develoop](http://deploop.github.io/) - tool for provisioning, managing and monitoring Apache Hadoop.
* [Etsy Sahale](https://codeascraft.com/2015/02/11/sahale-visualizing-cascading-workflows-at-etsy/) - Visualizing Cascading Workflows at Etsy.
* [Facebook Autoscale](https://code.facebook.com/posts/816473015039157/making-facebook-s-software-infrastructure-more-energy-efficient-with-autoscale/) - the load balancer will concentrate workload to a server until it has at least a medium-level workload.
* [Facebook Prism](http://www.wired.com/2012/08/facebook-prism/) - multi datacenters replication system.
* [Ganglia Monitoring System](http://ganglia.sourceforge.net/) - scalable distributed monitoring system for high-performance computing systems such as clusters and Grids.
* [Genie](https://github.com/Netflix/genie) - Genie provides REST-ful APIs to run Hadoop, Hive and Pig jobs, and to manage multiple Hadoop resources and perform job submissions across them..
* [Google Borg](http://www.wired.com/wiredenterprise/2013/03/google-borg-twitter-mesos/all/) - job scheduling and monitoring system.
* [Google Omega](https://www.youtube.com/watch?v=0ZFMlO98Jkc) - job scheduling and monitoring system.
* [Hannibal](https://github.com/sentric/hannibal) - Hannibal is tool to help monitor and maintain HBase-Clusters that are configured for manual splitting..
* [Hortonworks HOYA](http://hortonworks.com/blog/introducing-hoya-hbase-on-yarn/) - application that can deploy HBase cluster on YARN.
* [Jumbune](http://www.jumbune.org/) - Jumbune is an open-source product built for analyzing Hadoop cluster and MapReduce jobs..
* [Marathon](https://github.com/mesosphere/marathon) - Mesos framework for long-running services.
* [Minotaur](https://github.com/stealthly/minotaur) - scripts/recipes/configs to spin up VPC-based infrastructure in AWS from scratch and deploy labs to it.
* [Myriad](https://github.com/mesos/myriad) - a mesos framework designed for scaling YARN clusters on Mesos. Myriad can expand or shrink one or more YARN clusters in response to events as per configured rules and policies..
* [Neflix SimianArmy](https://github.com/Netflix/SimianArmy) - a suite of tools for keeping your cloud operating in top form.
* [Netflix Eureka](https://github.com/Netflix/eureka) - AWS Service registry for resilient mid-tier load balancing and failover.
* [Netflix Hystrix](https://github.com/Netflix/Hystrix) - a latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable.
* [Scaling Data](http://www.scalingdata.com/big-data) - tracing data center problems to root cause, predict capacity issues, identify emerging failures and highlight latent threats.
* [Tumblr Collins](http://tumblr.github.io/collins/) - Infrastructure management for engineers.
* [Tumblr Genesis](http://tumblr.github.io/genesis/) - a tool for data center automation.

## Container Manager

* [Amazon EC2 Container Service](https://aws.amazon.com/ecs/) - a highly scalable, high performance container management service that supports Docker containers.
* [Docker](https://www.docker.com/) - an open platform for developers and sysadmins to build, ship, and run distributed applications.
* [Fig](http://www.fig.sh/) - fast, isolated development environments using Docker.
* [Google Container Engine](https://cloud.google.com/container-engine/) - Run Docker containers on Google Cloud Platform, powered by Kubernetes.
* [Kubernetes](https://github.com/GoogleCloudPlatform/kubernetes) - open source implementation of container cluster management.
* [Rocket](https://coreos.com/blog/rocket/) - an alternative to the Docker runtime, designed for server environments with the most rigorous security and production requirements.

## Applications

* [Adobe Spindle](https://github.com/adobe-research/spindle) - Next-generation web analytics processing with Scala, Spark, and Parquet.
* [Apache Kiji](http://www.kiji.org/) - framework to collect and analyze data in real-time, based on HBase.
* [Apache Nutch](http://nutch.apache.org/) - open source web crawler.
* [Apache OODT](http://oodt.apache.org/) - capturing, processing and sharing of data for NASA's scientific archives.
* [Apache Tika](https://tika.apache.org/) - content analysis toolkit.
* [Domino](http://www.dominoup.com/) - Run, scale, share, and deploy models Ñ without any infrastructure..
* [Eclipse BIRT](http://www.eclipse.org/birt/) - Eclipse-based reporting system.
* [Eventhub](https://github.com/Codecademy/EventHub) - open source event analytics platform.
* [HIPI Library](http://hipi.cs.virginia.edu/) - API for performing image processing tasks on Hadoop's MapReduce.
* [Hunk](http://www.splunk.com/download/hunk) - Splunk analytics for Hadoop.
* [MADlib](http://madlib.net/community/) - data-processing library of an RDBMS to analyze data.
* [PivotalR](https://github.com/gopivotal/PivotalR) - R on Pivotal HD / HAWQ and PostgreSQL.
* [Qubole](http://www.qubole.com/) - auto-scaling Hadoop cluster, built-in data connectors.
* [Sense](https://senseplatform.com/) - Cloud Platform for Data Science and Big Data Analytics.
* [Snowplow](https://github.com/snowplow/snowplow) - enterprise-strength web and event analytics, powered by Hadoop, Kinesis, Redshift and Postgres.
* [SparkR](http://amplab-extras.github.io/SparkR-pkg/) - R frontend for Spark.
* [Splunk](http://www.splunk.com/) - analyzer for machine-generated date.
* [Talend](http://www.talend.com/products/big-data) - unified open source environment for YARN, Hadoop, HBASE, Hive, HCatalog & Pig.

## Search engine and framework

* [Apache Blur](https://incubator.apache.org/blur/) - a search engine capable of querying massive amounts of structured data at incredible speeds.
* [Apache Lucene](http://lucene.apache.org/) - Search engine library.
* [Apache Solr](http://lucene.apache.org/solr/) - Search platform for Apache Lucene.
* [ElasticSearch](http://www.elasticsearch.org/) - Search and analytics engine based on Apache Lucene.
* [Elasticsearch Hadoop](https://github.com/elasticsearch/elasticsearch-hadoop) - Elasticsearch real-time search and analytics natively integrated with Hadoop. Supports Map/Reduce, Cascading, Apache Hive and Apache Pig..
* [Enigma.io](http://enigma.io) - Freemium robust web application for exploring, filtering, analyzing, searching and exporting massive datasets scraped from across the Web.
* [Facebook Unicorn](https://www.facebook.com/publications/219621248185635/) - social graph search platform.
* [Google Caffeine](http://googleblog.blogspot.it/2010/06/our-new-search-index-caffeine.html) - continuous indexing system.
* [Google Percolator](http://research.google.com/pubs/pub36726.html) - continuous indexing system.
* [TeraGoogle]() - large search index.
* [Haeinsa](https://github.com/VCNC/haeinsa) - linearly scalable multi-row, multi-table transaction library for HBase based on Percolator.
* [HBase Coprocessor](https://blogs.apache.org/hbase/entry/coprocessor_introduction) - implementation of Percolator, part of HBase.
* [hIndex](https://github.com/Huawei-Hadoop/hindex) - Secondary Index for HBase.
* [SF1R Search Engine](http://github.com/izenecloud/sf1r-lite) - distributed search engine written in c++.
* [Lily HBase Indexer](http://ngdata.github.io/hbase-indexer/) - quickly and easily search for any content stored in HBase.
* [LinkedIn Bobo](http://senseidb.github.io/bobo/) - is a Faceted Search implementation written purely in Java, an extension to Apache Lucene.
* [LinkedIn Cleo](https://github.com/linkedin/cleo) - is a flexible software library for enabling rapid development of partial, out-of-order and real-time typeahead search.
* [LinkedIn Galene](http://engineering.linkedin.com/search/did-you-mean-galene) - search architecture at LinkedIn.
* [LinkedIn Zoie](https://github.com/senseidb/zoie) - is a realtime search/indexing system written in Java.
* [Sphnix Search Server](http://sphinxsearch.com/) - fulltext search engine.

## MySQL forks and evolutions

* [Amazon Aurora](https://aws.amazon.com/rds/aurora/) - a MySQL-compatible, relational database engine that combines the speed and availability of high-end commercial databases with the simplicity and cost-effectiveness of open source databases.
* [Amazon RDS](http://aws.amazon.com/rds/) - MySQL databases in Amazon's cloud.
* [Drizzle](http://www.drizzle.org/) - evolution of MySQL 6.0.
* [Google Cloud SQL](https://developers.google.com/cloud-sql/) - MySQL databases in Google's cloud.
* [HiveDB](http://www.hivedb.org/) - an open source framework for horizontally partitioning MySQL systems.
* [MariaDB](https://mariadb.org/) - enhanced, drop-in replacement for MySQL.
* [MariaDB Galera](https://mariadb.com/kb/en/mariadb/documentation/replication/galera/) - a synchronous multi-master cluster for MariaDB.
* [MySQL Cluster](http://www.mysql.com/products/cluster/) - MySQL implementation using NDB Cluster storage engine providing shared-nothing clustering and auto-sharding.
* [Percona Server](http://www.percona.com/software/percona-server) - enhanced, drop-in replacement for MySQL.
* [ProxySQL](https://github.com/renecannao/proxysql) - High Performance Proxy for MySQL.
* [TokuDB](http://www.tokutek.com/products/tokudb-for-mysql/) - TokuDB is a storage engine for MySQL and MariaDB.
* [WebScaleSQL](http://webscalesql.org/) - is a collaboration among engineers from several companies that face similar challenges in running MySQL at scale.
* [Youtube Vitess](https://github.com/youtube/vitess) - provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

## PostgreSQL forks and evolutions

* [HadoopDB](http://db.cs.yale.edu/hadoopdb/hadoopdb.html) - hybrid of MapReduce and DBMS.
* [IBM Netezza](http://www-01.ibm.com/software/data/netezza/) - high-performance data warehouse appliances.
* [Postgres-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster.
* [RecDB](http://www-users.cs.umn.edu/~sarwat/RecDB/) - Open Source Recommendation Engine Built Entirely Inside PostgreSQL.
* [Stado](http://www.stormdb.com/community/stado) - open source MPP database system solely targeted at data warehousing and data mart applications.
* [Yahoo Everest](http://www.scribd.com/doc/3159239/70-Everest-PGCon-RT) - multi-peta-byte database / MPP derived by PostgreSQL.

## Memcached forks and evolutions

* [Box Tron](http://engineering.opendns.com/2014/09/16/caching-scale/) - proxy to memcached servers.
* [Facebook McDipper](https://www.facebook.com/notes/facebook-engineering/mcdipper-a-key-value-cache-for-flash-storage/10151347090423920) - key/value cache for flash storage.
* [Facebook Mcrouter](https://github.com/facebook/mcrouter) - a memcached protocol router for scaling memcached deployments.
* [Facebook Memcached](https://www.facebook.com/notes/facebook-engineering/scaling-memcache-at-facebook/10151411410803920) - fork of Memcache.
* [Twemproxy](https://github.com/twitter/twemproxy) - A fast, light-weight proxy for memcached and redis.
* [Twitter Fatcache](https://github.com/twitter/fatcache) - key/value cache for flash storage.
* [Twitter Twemcache](https://github.com/twitter/twemcache) - fork of Memcache.

## Embedded Databases

* [Actian PSQL](http://www.actian.com/products/operational-databases/) - ACID-compliant DBMS developed by Pervasive Software, optimized for embedding in applications.
* [BerkeleyDB](http://www.oracle.com/us/products/database/berkeley-db/overview/index.html) - a software library that provides a high-performance embedded database for key/value data.
* [eXtreme DB](http://www.mcobject.com/extremedbfamily.shtml) - in-memory database combines exceptional performance, reliability and developer efficiency in a proven real-time embedded database engine.
* [FairCom c-treeACE](http://www.faircom.com/ace/ace_t.php) - a cross-platform database engine.
* [Google Firebase](https://www.firebase.com/) - a powerful API to store and sync data in realtime.
* [HamsterDB](http://hamsterdb.com/) - transactional key-value database.
* [HanoiDB](https://github.com/krestenkrab/hanoidb) - Erlang LSM BTree Storage.
* [LevelDB](https://code.google.com/p/leveldb/) - a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.
* [LMDB](http://symas.com/mdb/) - ultra-fast, ultra-compact key-value embedded data store developed by Symas.
* [RocksDB](http://rocksdb.org/) - embeddable persistent key-value store for fast storage based on LevelDB.
* [TokioCabinet](http://fallabs.com/tokyocabinet/) - a library of routines for managing a database.

## Business Intelligence

* [ActivePivot](http://quartetfs.com/products/activepivot) - Java In-Memory OLAP cube stored in columns, with clearly decoupled pre/post processing.
* [Adatao](http://adatao.com/pinsights.html) - business intelligence and data science platform.
* [Apama analytics](http://www.softwareag.com/corporate/products/bigdata/apama_analytics/overview/) - platform for streaming analytics and intelligent automated action.
* [Atigeo xPatterns](http://xpatterns.com/) - data analytics platform.
* [BIME Analytics](http://www.bimeanalytics.com/) - business intelligence platform in the cloud.
* [Chartio](https://chartio.com) - lean business intelligence platform to visualize and explore your data.
* [Datapine](http://www.datapine.com/) - self-service business intelligence tool in the cloud.
* [Jaspersoft](https://www.jaspersoft.com/) - powerful business intelligence suite.
* [Jedox Palo](http://www.jedox.com/) - customisable Business Intelligence platform.
* [Lavastorm Analytics](http://www.lavastorm.com/) - used for audit analytics, revenue assurance, fraud management, and customer experience management.
* [LinkedIn GoSpeed](http://engineering.linkedin.com/performance/monitor-and-improve-web-performance-using-rum-data-visualization) - provides RUM data processing, visualization, monitoring, and analyses data daily, hourly, or on a near real-time basis.
* [Map-D](http://www.map-d.com/) - GPU in-memory database, big data analysis and visualization platform.
* [Microsoft](http://www.microsoft.com/en-us/server-cloud/solutions/business-intelligence/default.aspx) - business intelligence software and platform.
* [Microstrategy](http://www.microstrategy.com/) - software platforms for business intelligence, mobile intelligence, and network applications.
* [Pentaho](http://www.pentaho.com/) - business intelligence platform.
* [Qlik](http://www.qlik.com/) - business intelligence and analytics platform.
* [SpagoBI](http://www.spagoworld.org/xwiki/bin/view/SpagoBI/) - open source business intelligence platform.
* [Spotfire](http://spotfire.tibco.com/) - business intelligence platform.
* [Tableau](https://www.tableausoftware.com/) - business intelligence platform.
* [Teradata Aster](http://it.teradata.com/Teradata-Aster-Database/) - Big Data Analytics.
* [Tessera](http://tesseradata.org/) - Environment for Deep Analysis of Large Complex Data.
* [Zeppelin](http://zeppelin-project.org/) - open source data analysis environment on top of Hadoop..
* [Zoomdata](http://www.zoomdata.com/) - Big Data Analytics.

## Data Analysis

* [Datameer](http://www.datameer.com/product/index.html) - data analytics application for Hadoop combines self-service data integration, analytics and visualization.
* [LinkedIn Pinot](http://engineering.linkedin.com/analytics/real-time-analytics-massive-scale-pinot) - a distributed system that supports columnar indexes with the ability to add new types of indexes.
* [Myria](http://myria.cs.washington.edu/) - scalable Analytics-as-a-Service platform based on relational algebra.
* [Pinalytics](http://engineering.pinterest.com/post/104418761649/building-pinalytics-pinterests-data-analytics) - Pinterestâs data analytics engine.
* [Zillabyte](http://zillabyte.com/) - an API for distributed data computation. Scale with your data..

## Data Warehouse

* [Google Mesa](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/42851.pdf) - highly scalable analytic data warehousing system.
* [IBM BigInsights](http://www.ibm.com/software/data/infosphere/biginsights/) - data processing, warehousing and analytics.
* [IBM dashDB](https://cloudant.com/dashdb/) - Data Warehousing and Analysis Needs, all in the Cloud.
* [Microsoft Cosmos](http://research.microsoft.com/en-us/events/fs2011/helland_cosmos_big_data_and_big_challenges.pdf) - Microsoft's internal BigData analysis platform.

## Data Visualization

* [Arbor](https://github.com/samizdatco/arbor) - graph visualization library using web workers and jQuery.
* [C3](http://c3js.org/) - D3-based reusable chart library.
* [CartoDB](https://github.com/CartoDB/cartodb) - open-source or freemium hosting for geospatial databases with powerful front-end editing capabilities and a robust API.
* [Chart.js](http://www.chartjs.org/) - open source HTML5 Charts visualizations.
* [Chartist.js](https://github.com/gionkunz/chartist-js) - another open source HTML5 Charts visualization.
* [Crossfilter](http://square.github.io/crossfilter/) - avaScript library for exploring large multivariate datasets in the browser. Works well with dc.js and d3.js.
* [Cubism](https://github.com/square/cubism) - JavaScript library for time series visualization.
* [Cytoscape](http://cytoscape.github.io/) - JavaScript library for visualizing complex networks.
* [D3](http://d3js.org/) - javaScript library for manipulating documents.
* [DC.js](http://dc-js.github.io/dc.js/) - Dimensional charting built to work natively with crossfilter rendered using d3.js. Excellent for connecting charts/additional metadata to hover events in D3.
* [Envisionjs](https://github.com/HumbleSoftware/envisionjs) - dynamic HTML5 visualization.
* [FnordMetric ChartSQL](http://fnordmetric.io/chartsql/) - allows you to write SQL queries that return charts instead of tables. The charts are rendered as SVG vector graphics..
* [Freeboard](https://github.com/Freeboard/freeboard) - open source real-time dashboard builder for IOT and other web mashups.
* [Gephi](https://github.com/gephi/gephi) - An award-winning open-source platform for visualizing and manipulating large graphs and network connections.
* [Google Charts](https://developers.google.com/chart/) - simple charting API.
* [Grafana](http://grafana.org/) - open source, feature rich metrics dashboard and graph editor for  Graphite, InfluxDB & OpenTSDB.
* [Graphistry](http://www.graphistry.com/) - running on GPUs and turns static designs into interactive tools using client/cloud GPU infrastructure and GPU-accelerated languages like Superconductor.
* [Graphite](http://graphite.wikidot.com/) - scalable Realtime Graphing.
* [Highcharts](http://www.highcharts.com/) - simple and flexible charting API.
* [IPython](http://ipython.org/) - provides a rich architecture for interactive computing.
* [Keylines](http://keylines.com/) - toolkit for visualizing the networks in your data.
* [Kibana](http://www.elasticsearch.org/overview/kibana/) - visualize logs and time-stamped data.
* [Matplotlib](https://github.com/matplotlib/matplotlib) - plotting with Python.
* [NVD3](http://nvd3.org/) - chart components for d3.js.
* [Peity](https://github.com/benpickles/peity) - Progressive SVG bar, line and pie charts.
* [Plot.ly](http://plot.ly) - Easy-to-use web service that allows for rapid creation of complex charts, from heatmaps to histograms. Upload data to create and style charts with Plotly's online spreadsheet. Fork others' plots..
* [Recline](https://github.com/okfn/recline) - simple but powerful library for building data applications in pure Javascript and HTML.
* [Redash](https://github.com/everythingme/redash) - open-source platform to query and visualize data.
* [Sigma.js](https://github.com/jacomyal/sigma.js) - JavaScript library dedicated to graph drawing.
* [Square Cubism.js](http://square.github.io/cubism/) - aÊD3Êplugin for visualizing time series. Use Cubism to construct better realtime dashboards, pulling data fromÊGraphite,ÊCubeÊand other sources.
* [Vega](https://github.com/trifacta/vega) - a visualization grammar.

## Internet of Things

* [2lemetry](http://2lemetry.com/) - Platform for Internet of things.
* [Evrything](https://evrythng.com/) - Making products smart.
* [ThingWorx](http://www.thingworx.com/) - Rapid development and connection of intelligent systems.
