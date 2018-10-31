# SourceApi
The Source API will get or create a sourceId in the metadata database based on physical object and observed object.
This sourceId is needed for each telemetry message which is sent to the IoT Platform.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. The included [Maven Wrapper]((https://github.com/takari/maven-wrapper)) 

### Prerequisites

To run the project Java 8 [SDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) or [JRE](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) needs to be installed.

### Testing

To run the unit-tests in the project execute the following command:

```
./mvnw test
```

or

```
./mvnw.cmd test
```

### Packaging

To package the project as a jar execute the following command:

```
./mvnw package
```

or

```
./mvnw.cmd package
```

### Running

To run the project execute the following command:

```
./mvnw spring-boot:run
```
or
```
./mvnw.cmd spring-boot:run
```

### Api Documentation

You can view the api documentation in swagger-ui by pointing to  
http://localhost:8080/ after running the application locally.

You can change default port value in application.properties under resources.

The Api contract can be seen in yaml-format in sourceApi.yaml under resources.
