# config-server
The Spring boot Config Server is a centralized configuration server that manages and distributes configuration properties for multiple Spring boot applications.

Setup
## Prerequisites
- Java 17 or higher
- Maven 5.7.43

## Running the Application

To run the Config server application locally, follow these steps:

1. Clone this repository to your local machine:
   https://github.com/vasanthekumar/config-server.git
2. Navigate to the project directory:
   cd config-server
3. Build the application using Maven
   mvn clean install
4. Run the application:
   java -jar config-server-0.0.1-SNAPSHOT.jar
5. Access the Config server dashboard in your web browser:
   http://localhost:8191/

## Congiguration

The Config server application can be configured using application properties.
~`server.port`: The port number on which the Config server listens for incoming requests.
~`spring.cloud.config.server.git.uri`: The Git repository URL that contains the configuration files.
~`spring.cloud.config.server.git.search-paths`: The Git repository search path where the Config Server should look from configuration files. 