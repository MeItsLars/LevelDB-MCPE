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
    <groupId>com.github.MeItsLars</groupId>
    <artifactId>LevelDB-MCPE</artifactId>
    <version>1.0.2</version>
</dependency>
```

I do NOT claim any ownership of the LevelDB project, original or Java wrapper.
Credits for the LevelDB Java Wrapper go to Dain and Tinfoiled.
