# demo  Spring Boot REST CRUD API

# Steps to Setup
# Clone the application
https://github.com/jubydullakber/demo.git

open src/main/resources/application.properties

change spring.datasource.url,spring.datasource.driverClassName,spring.datasource.username and spring.datasource.password as per your DB installation

# Build and run the app using maven

  mvn package
  java -jar target/spring-boot-rest-api-tutorial-0.0.1-SNAPSHOT.jar
  Alternatively, you can run the app without packaging it using -

  mvn spring-boot:run
  The app will start running at http://localhost:8100

# Api Documentation
 For Api Documentation used Open API url http://localhost:8080/swagger-ui/index.html

# Postmant Collention
 Postman collection also find in this repo.

# Container
For Containerize used Docker.can run with command docker-compose up.

#Trace
For distributed tracing used zipkin server.url : http://localhost:9411/zipkin/

