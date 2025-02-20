# Apache HCatalog<a name="emr-hcatalog"></a>

HCatalog is a tool that allows you to access Hive metastore tables within Pig, Spark SQL, and/or custom MapReduce applications\. HCatalog has a REST interface and command line client that allows you to create tables or do other operations\. You then write your applications to access the tables using HCatalog libraries\. For more information, see [Using HCatalog](https://cwiki.apache.org/confluence/display/Hive/HCatalog+UsingHCat)\. HCatalog is included in Amazon EMR release version 4\.4\.0 and later\.

HCatalog on Amazon EMR release version 5\.8\.0 and later supports using AWS Glue Data Catalog as the metastore for Hive\. For more information, see [Using AWS Glue Data Catalog as the Metastore for Hive](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-hive-metastore-glue.html)\.

The following table lists the version of HCatalog included in the latest release of Amazon EMR 6\.x series, along with the components that Amazon EMR installs with HCatalog\.

For the version of components installed with HCatalog in this release, see [Release 6\.2\.0 Component Versions](emr-release-6x.md#emr-620-release)\.


**HCatalog Version Information for emr\-6\.2\.0**  

| Amazon EMR Release Label | HCatalog Version | Components Installed With HCatalog | 
| --- | --- | --- | 
| emr\-6\.2\.0 | HCatalog 3\.1\.2 | emrfs, emr\-ddb, emr\-goodies, emr\-kinesis, hadoop\-client, hadoop\-mapred, hadoop\-hdfs\-datanode, hadoop\-hdfs\-library, hadoop\-hdfs\-namenode, hadoop\-kms\-server, hadoop\-yarn\-nodemanager, hadoop\-yarn\-resourcemanager, hadoop\-yarn\-timeline\-server, hcatalog\-client, hcatalog\-server, hcatalog\-webhcat\-server, hive\-client, mariadb\-server | 

The following table lists the version of HCatalog included in the latest release of Amazon EMR 5\.x series, along with the components that Amazon EMR installs with HCatalog\.

For the version of components installed with HCatalog in this release, see [Release 5\.32\.0 Component Versions](emr-release-5x.md#emr-5320-release)\.


**HCatalog Version Information for emr\-5\.32\.0**  

| Amazon EMR Release Label | HCatalog Version | Components Installed With HCatalog | 
| --- | --- | --- | 
| emr\-5\.32\.0 | HCatalog 2\.3\.7 | emrfs, emr\-ddb, emr\-goodies, emr\-kinesis, hadoop\-client, hadoop\-mapred, hadoop\-hdfs\-datanode, hadoop\-hdfs\-library, hadoop\-hdfs\-namenode, hadoop\-kms\-server, hadoop\-yarn\-nodemanager, hadoop\-yarn\-resourcemanager, hadoop\-yarn\-timeline\-server, hcatalog\-client, hcatalog\-server, hcatalog\-webhcat\-server, hive\-client, mariadb\-server | 

**Topics**
+ [Creating a Cluster with HCatalog](emr-hcatalog-create-cluster.md)
+ [Using HCatalog](emr-hcatalog-using.md)
+ [Example: Create an HCatalog Table and Write to it Using Pig](emr-hcatalog-pig.md)
+ [HCatalog Release History](HCatalog-release-history.md)