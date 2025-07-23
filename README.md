# BasicSpringBootWebApplication
A  simple web application built with Spring Boot

Open terminal

cd demo

run the following command:

./mvnw spring-boot:run

In a separate terminal window), run the following commands:

curl http://localhost:8080

curl http://localhost:8080/actuator/health

Remove-item alias:curl

curl -X POST http://localhost:8080/actuator/shutdown
