![Eclipse JNoSQL Archetype Project](https://github.com/JNOSQL/diana-site/blob/master/images/duke-diana.png)
# Eclipse JNoSQL Archetype

This project contains quick start to Eclipse JNoSQL project using the Maven Archetype.

## Java SE

The archetypes that run Eclipse JNoSQL using [CDI 2.0](https://jcp.org/en/jsr/detail?id=365), [JSON-B](https://jcp.org/en/jsr/detail?id=367) and [JSON-P](https://www.jcp.org/en/jsr/detail?id=374), where by default it uses the Reference implementation to each implementation, thereby Eclipse Yasson, Eclipse Glassfish JSON, and Weld respectively.


### KeyValue SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-key-value  -DarchetypeVersion=0.0.1  -DgroupId=com.company  -DartifactId=nosql-sample -Dversion=0.0.1 -DinteractiveMode=false`

### Column Family SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-column  -DarchetypeVersion=0.0.1  -DgroupId=com.company  -DartifactId=nosql-sample -Dversion=0.0.1 -DinteractiveMode=false`

### Document SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-document  -DarchetypeVersion=0.0.1  -DgroupId=com.company  -DartifactId=nosql-sample -Dversion=0.0.1 -DinteractiveMode=false`

### Graph SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-graph  -DarchetypeVersion=0.0.1  -DgroupId=com.company  -DartifactId=nosql-sample -Dversion=0.0.1 -DinteractiveMode=false`
