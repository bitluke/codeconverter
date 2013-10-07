Codeconverter
=============
This tool is capable of transforming an android application into a code offloadable application .

Requirements
-------------
Maven : version >= 2
JDK : version >= 1.6

Build
------------
Download the source and navigate into the root directory. Execute the code below 

```xml
mvn clean install
````
Then move into the converter directory and run 

```xml
mvn org.apache.maven.plugins:maven-assembly-plugin:2.2-beta-2:assembly
````

Try Application 
------------
A file "converter-1.0-jar-with-dependencies" would be created in target folder of the converter directory.
Navigate into the directory via the command prompt and execute the following

```xml
java -jar converter-1.0-jar-with-dependencies
````