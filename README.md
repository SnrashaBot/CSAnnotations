Install the local jar:

Launch on the directory CSAnnotations:

Compile the jar: 
```
mvn [optional]clean package 
```

Install the jar:
```
mvn install:install-file -Dfile=./target/CodeSmellsAnnotations.jar -DpomFile=./pom.xml
```


Then on your pom.xml, you can put the dependency:
Maven:
```
<dependency>
	<groupId>codesmells.annotations</groupId>
	<artifactId>CSAnnotations</artifactId>
	<version>1</version>
</dependency>
```