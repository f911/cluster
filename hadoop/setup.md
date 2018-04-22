# The hadoop setup process



# single node
wget hadoop binary

    wget http://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.1.0/hadoop-3.1.0.tar.gz

## set jdk & hadoop environment varibles


## config file list 

* core-site.xml
* yarn-site.xml
* mapred-site.xml
* hdfs-site.xml


## add hdfs dir

    $HADOOP_HOME/data/hdfs/namenode
    $HADOOP_HOME/data/hdfs/datanode

## create log file auto

    $HADOOP_HOME/logs
