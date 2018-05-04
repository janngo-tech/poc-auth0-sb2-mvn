Adaptation of Auth0 tutorial for implementing authentication with Spring Security.

The original tutorial is here: [Original Tutorial](https://auth0.com/docs/quickstart/webapp/java-spring-security-mvc/01-login)

Adaptations:
* use Maven instead of Graddle
* use Spring Boot 2

To run the application:
* make the required configuration on the [Auth0 Dashboard](https://manage.auth0.com/#/clients) as explained in the [Original Tutorial](https://auth0.com/docs/quickstart/webapp/java-spring-security-mvc/01-login)
* set the client values in the `src/main/resources/auth0.properties` file
* in a terminal, execute: ```mvnw spring-boot:run```

The server will be accessible on [https://localhost:3000/portal/home](https://localhost:3000/portal/home).

Original Author: [Auth0](https://auth0.com)

This project is licensed under the MIT license. See the [LICENSE](/LICENSE) file for more info.

