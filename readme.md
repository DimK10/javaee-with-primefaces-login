## Template JavaEE Project with Primefaces

To run this project, run:
```
mvn clean install && mvn wildfly:run
```

The project might give an error about jconsole.jar file. If thats the case, you can use Java 8 and make 
JAVA_HOME enviroment variable point to Java 8 (jconsole.jar is not included in newer versions)

The login page is not added yet