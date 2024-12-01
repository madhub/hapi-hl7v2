# Build instructions for building the HL7 Test Panel
### prerequisites
1.  JDK  11 or higher https://jdk.java.net/java-se-ri/11-MR3
2.  Maven https://maven.apache.org/download.cgi

on Windows
```shell
set JAVA_HOME=<<path_of_jdk>>
set MAVEN_HOME=<<path_of_jdk>>
set PATH=%JAVA_HOME%\bin;%MAVEN_HOME%\bin;%PATH%
cd hapi-testpanel
# build creates a fat jar with all dependencies java -jar hapi-testpanel-2.6.0-SNAPSHOT-jar-with-dependencies.jar
mvn

# run app using
java -jar hapi-testpanel-2.6.0-SNAPSHOT-jar-with-dependencies.jar

```
