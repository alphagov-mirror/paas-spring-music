Spring Music
============

This is a sample application for using database services on [Cloud Foundry](http://cloudfoundry.org) with the [Spring Framework](http://spring.io) and [Spring Boot](http://projects.spring.io/spring-boot/).

This application has been built to store the same domain objects in one of a variety of different persistence technologies - relational, document, and key-value stores. This is not meant to represent a realistic use case for these technologies, since you would typically choose the one most applicable to the type of data you need to store, but it is useful for testing and experimenting with different types of services on Cloud Foundry.

The application use Spring Java configuration and [bean profiles](http://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-profiles.html) to configure the application and the connection objects needed to use the persistence stores. It also uses the [Spring Cloud Connectors](http://cloud.spring.io/spring-cloud-connectors/) library to inspect the environment when running on Cloud Foundry. See the [Cloud Foundry documentation](http://docs.cloudfoundry.org/buildpacks/java/spring-service-bindings.html) for details on configuring a Spring application for Cloud Foundry.

## Tutorial
Please follow these step-by-step scenarios to build and deploy **Spring Music**:
 - [Scenario 1](./scenarios/scenario-01): Building and Deploying the app locally.
 - [Scenario 2](./scenarios/scenario-02): Deploying the app to Cloud Foundry and binding it to data service.
 - [Scenario 3](./scenarios/scenario-03): Dockerize the app and run it as a docker container locally.
 - [Scenario 4](./scenarios/scenario-04): Deploying the docker image (e.g. dockerized app) to Cloud Foundry and binding it to data service..
 
 
 
 
