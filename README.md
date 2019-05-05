# Usage

In your pom.xml, add this repository as a repo:

```xml
    ...
    <repositories>
        <repository>
            <id>project-common</id>
            <name>Project Common</name>
            <url>https://github.com/mboysan/mvn-repo/raw/master</url>
        </repository>
    </repositories>
   ...
```

Add one of the dependencies available like the following:

```xml
	...
    <dependencies>
        <dependency>
            <groupId>ee.mboysan</groupId>
            <artifactId>signverify</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
		...
    </dependencies>
	...
```
