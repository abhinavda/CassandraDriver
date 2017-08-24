# CassandraDriver

Add the following dependencies in POM

```xml
<dependency>
  <groupId>com.datastax.cassandra</groupId>
  <artifactId>cassandra-driver-core</artifactId>
  <version>3.3.0</version>
</dependency>
<<<<<<< HEAD
```
=======

Note that the object mapper is published as a separate artifact:
>>>>>>> 018f5432cfee9f3f38eef7d8a4337b97ffc38c82

Note that the object mapper is published as a separate artifact:
```xml
<dependency>
  <groupId>com.datastax.cassandra</groupId>
  <artifactId>cassandra-driver-mapping</artifactId>
  <version>3.3.0</version>
</dependency>
```
The 'extras' module is also published as a separate artifact:
```xml
<dependency>
  <groupId>com.datastax.cassandra</groupId>
  <artifactId>cassandra-driver-extras</artifactId>
  <version>3.3.0</version>
</dependency>
```
