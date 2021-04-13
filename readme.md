## Tutorial for Spark based on docker compose
SW Park

### 1. Introduce
- To prepare spark teaching assistant on MODULAB, It is prepared.
- ref 
    > Repository : big-data-europe/docker-spark  
    > https://github.com/big-data-europe/docker-spark  
    > docker hub : https://hub.docker.com/u/bde2020  


### 2. Environment
- Docker Cluster (base: big-data-europe/docker-spark)  
  > Image : bde2020/spark-master:3.0.0-hadoop3.2-java11  
  > Image layers : https://hub.docker.com/layers/bde2020/spark-master/3.0.0-hadoop3.2-java11/images/sha256-b5f9569b5e426d08fdeaeecdec0dae38d99a9e5a2a825285670e87e706a21620?context=explore  
  
  - Step 1. prepared image
    - OpenJDK 11
    - Hadoop 3.2
    - Spark 3.0.0
        - ref : https://spark.apache.org/releases/spark-release-3-0-0.html
    -  Scala 2.12
  - Step 2. Newly built Image  
  ref : https://hub.docker.com/r/psyoblade/docker-sqoop  
  ref : dockerfile : 
    
    - Sqoop
    - Requirement over Hadoop 2.6.0
    - ref : https://sqoop.apache.org/docs/1.99.7/admin/Installation.html


#### ex. What's difference between Sqoop and Hive  
ref : https://stackoverflow.com/questions/26346021/differences-between-apache-sqoop-and-hive-can-we-use-both-together

- Hadoop database : HDFS (No SQL DB)
- Sqoop : Integration of DBs (SQL,No SQL and Data Lakes)
- HQL => Hive SQL / 약간

### 3. Spark based API

#### 3.1. HTTP API
- on-going


