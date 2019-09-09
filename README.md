# BikeShop Cloud Native Application

This is an example application using cloud-native principles.

The applcation is made up of the following components:

* A user interface (UI) implemented in Angular.
* A REST web services API, with two implementation options:
  * One written in Java using Spring Boot
  * One written using C# .NET Core and Steeltoe

The application can be deployed into PCF.

## Requirements

To do each of the labs, you should have the following installed and configured:

1. An IDE or text editor, such as:
   1. VS Code
   1. Atom
   1. IDEA IntelliJ
   1. SpringSource Tool Suite
1. The [Java JDK from OpenJDK](http://openjdk.java.net/install/index.html).
1. The [CloudFoundry CLI](https://docs.run.pivotal.io/cf-cli/install-go-cli.html).

## User Interface (Angular)

The BikeShop application's user interface (UI) is implemented in Angular and can
use either the .NET API or the Spring Boot-based API for its REST backend.

*The UI is yet-to-be pushed*

## Spring Boot REST API

The REST API implemented in Spring Boot can be found in the `SpringApi` directory.
