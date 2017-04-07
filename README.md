# 20.3


Writables and its Importance in Hadoop

Writable is an interface in Hadoop. Writable in Hadoop acts as a wrapper class to almost all the primitive data type of Java. That is how int of java has become IntWritable in Hadoop and String of Java has become Text in Hadoop.

Writables are used for creating serialized data types in Hadoop.
Hadoop. Hadoop frame work definitely needs Writable type of interface in order to perform the following tasks:

Implement serialization
Transfer data between clusters and networks
Store the deserialized data in the local disk of the system
