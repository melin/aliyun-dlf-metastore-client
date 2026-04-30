### Build
```
export GPG_TTY=$(tty)
mvn clean deploy -Pdeploy
```

```xml
<dependency>
    <groupId>com.github.melin</groupId>
    <module>metastore-client-hive3</module>
    <version>1.0.0</version>
</dependency>

<dependency>
    <groupId>com.github.melin</groupId>
    <module>metastore-client-hive2</module>
    <version>1.0.0</version>
</dependency>
```
