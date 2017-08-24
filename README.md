# CassandraDriver

Add the following dependencies in POM

<dependency>
  <groupId>com.datastax.cassandra</groupId>
  <artifactId>cassandra-driver-core</artifactId>
  <version>3.3.0</version>
</dependency>
Note that the object mapper is published as a separate artifact:

<dependency>
  <groupId>com.datastax.cassandra</groupId>
  <artifactId>cassandra-driver-mapping</artifactId>
  <version>3.3.0</version>
</dependency>
The 'extras' module is also published as a separate artifact:

<dependency>
  <groupId>com.datastax.cassandra</groupId>
  <artifactId>cassandra-driver-extras</artifactId>
  <version>3.3.0</version>
</dependency>
