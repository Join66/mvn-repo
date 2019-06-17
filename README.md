# mvn-repo
a repository for storing jar packages

# specific steps

1. enter the directory where the jar package is located
2. mvn install:install-file -Dfile=helloworld.jar -DgroupId=com.repo -DartifactId=helloworld -Dversion=0.0.1 -Dpackaging=jar
3. git commit