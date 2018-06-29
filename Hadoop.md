## HDFS
Distributed file system as foundation  
1. scalable storage
2. Fault tolerance 

### Two key components
1. NameNode for metadata
- *one per cluster*
2. DataNode for block storage  
- *one per machine*

## YARN
Flexible scheduling and resource management

## MapReduce
Simplified programming model
1. map -> apply()
2. reduce -> summarize()

## Higer-level programming models
1. Pig: dataflow scripting
2. Hive: SQL-like queries

## Specialized models for graph processing
1. Giraph

## Real-time and in momory processing
Faster (100x)
1. Strom
2. Spark
3. Flink

## NoSQL for non-files
such as:
1. key-values
2. Sparse tables

## Zookeeper for management
functions:
1. Synchronization
2. Configuration
3. High-availability