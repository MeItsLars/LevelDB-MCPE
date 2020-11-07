# LevelDB-MCPE
LevelDB was originally made by Google. Dain made a Java wrapper library: https://github.com/dain/leveldb

Tinfoiled added ZLIB compression functionality: https://github.com/tinfoiled/leveldb

This repository is used to push this working MCPE LevelDB Jar to the jitpack.io maven repository, under the following coordinates:
```xml
<repositories>
	<repository>
	    <id>jitpack.io</id>
	    <url>https://jitpack.io</url>
	</repository>
</repositories>

<dependency>
    <groupId>nl.itslars</groupId>
    <artifactId>leveldb-mcpe</artifactId>
    <version>1.0.2</version>
</dependency>
```

Credits for the LevelDB project go to Dain and Tinfoile
