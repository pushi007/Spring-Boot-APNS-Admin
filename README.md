# Spring-Boot-Admin

##Overview
- Spring Boot Admin is built on Spring boot technology using Spring Actuator.
- It provides a web based user interface to monitor the running Spring boot rest services.
- Each spring boot service which needs to be monitored using this Spring boot admin service needs to register itself by adding a property in application.properties.


##Advantages of Spring-Boot-Admin
- Number of metrics can be generated to provide the statistical result of the running spring applicaion registered with this Admin utility.
- Memory usage of the running application can be monitored in real time.
- Component state whether running or stopped can be monitored.
- Gives a notification on your server/Desktop once the spring application being monitored is brought up or goes down.
- Transactions processing can be monitored whether success or failure inside the registered application while processing the transactions.
 
## Using Spring-Boot-Admin service
Any Spring boot application can be registered with this admin service by simply adding a property in application.properties file of running sprign boot application.
###Property to be added in application.properties file of the application which needs to be registered with Spring-Boot-Admin service :
`spring.boot.admin.url=http://server-name:8080`
