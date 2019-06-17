# mvn-repo

a repository for storing jar packages

# specific steps

1. enter the directory where the jar package is located
2. mvn install:install-file -Dfile=helloworld.jar -DgroupId=com.repo -DartifactId=helloworld -Dversion=0.0.1 -Dpackaging=jar
3. git commit

# reference

pom.xml
<repositories>
    <repository>
        <id>mvn-repo</id>
        <name>mvn-repo</name>
        <url>https://raw.github.com/Join66/mvn-repo/master</url>
    </repository>
</repositories>

<dependencies>
	<dependency>
		<groupId>com.repo</groupId>
		<artifactId>helloworld</artifactId>
		<version>0.0.1</version>
	</dependency>
</dependencies>