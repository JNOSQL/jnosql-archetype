![Eclipse JNoSQL Archetype Project](https://github.com/JNOSQL/diana-site/blob/master/images/duke-diana.png)
# Eclipse JNoSQL Archetype

This project contains quick start to Eclipse JNoSQL project using the Maven Archetype.

## Java SE

The archetypes that run Eclipse JNoSQL using [CDI 2.0](https://jcp.org/en/jsr/detail?id=365), [JSON-B](https://jcp.org/en/jsr/detail?id=367) and [JSON-P](https://www.jcp.org/en/jsr/detail?id=374), where by default it uses the Reference implementation to each implementation, thereby [Eclipse Yasson](http://json-b.net/), [Eclipse Glassfish JSON](https://javaee.github.io/jsonp/), and [Weld](http://weld.cdi-spec.org/).


### KeyValue SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-key-value  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`

### Column Family SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-column  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`

### Document SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-document  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`

### Graph SE

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=se-graph  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`


## Java Web

The archetypes that run Eclipse JNoSQL using Java EE, Jakarta EE as [API provided](https://mvnrepository.com/artifact/javax/javaee-api/8.0).


### KeyValue Web

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=web-key-value  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`

### Column Family Web

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=web-column  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`

### Document Web

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=web-document  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`

### Graph Web

`mvn archetype:generate -DarchetypeGroupId=org.jnosql.archetype   -DarchetypeArtifactId=web-graph  -DarchetypeVersion=0.0.6  -DgroupId=<groupId>  -DartifactId=<artifactId> -Dversion=<version> -DinteractiveMode=false`
