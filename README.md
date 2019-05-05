# Usage

In your pom.xml, add this repository as a repo:

```xml
	...

    <repositories>
        <repository>
            <id>project-common</id>
            <name>Project Common</name>
            <url>https://raw.githubusercontent.com/mboysan/mvn-repo/master/</url>
        </repository>
    </repositories>
```

Add one of the dependencies available like the following:

```xml
	...
	<dependencies>
        <dependency>
            <groupId>org.open-mpi</groupId>
            <artifactId>open-mpi</artifactId>
            <version>3.0.0</version>
        </dependency>
		...
	</dependencies>
	...
```