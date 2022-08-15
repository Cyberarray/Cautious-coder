# java-tomcat-maven-example

This is an example ready-to-deploy java web application built for Tomcat using Maven and webapp-runner.

## Running Locally

## (need maven and java installed)

```
mvn package
java -jar target/dependency/webapp-runner.jar target/*.war
```

The application will be available on `http://localhost:8080`.

## How This Was Built

1. Generate the project using a Maven archetype:

   ```
   mvn archetype:generate -DarchetypeArtifactId=maven-archetype-webapp
   ```


