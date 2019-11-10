# persistence-graphql
Sample Gradle Spring Boot Rest API with Junit 5. 
<https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/web/bind/annotation/RestController.html>  
<https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/stereotype/Service.html>  

## Workspace Setup
Download and install java <https://jdk.java.net/>  
Setting JAVA_HOME  <https://docs.oracle.com/cd/E19182-01/821-0917/inst_jdk_javahome_t/index.html>  
Download Eclipse <https://www.eclipse.org/downloads/packages/>  
Download and Install Gradle <https://docs.gradle.org/current/userguide/installation.html>  

## Running the application
Clone or download the project  
To run the application from Terminal / Command Prompt   
Change directory to the project root directory and type gradle bootRun  
To run the application inside Eclipse  
The starting point is Application.java  
Right click the Application.java  and select Run As ->Java Application  

## Database - h2
By default, Spring Boot will configure an H2 database for us  
H2 is a  database to develop against because it has an Oracle compatibility mode  
The application.properties initializes the datasource and the data.sql and schema.dql with initialize a sample db with a default user  
The h2 console can be accessed at the following location http://127.0.0.1:8080/h2-console  
To sign onto the console the credentials are in the following directory /src/main/resources/application.properties  
