# my-first-vertx-app
 my-first-vertx-app 
 
 Sample base on [Dzone Buiding reactive mircroservices Refcard ](https://dzone.com/storage/assets/5465811-building-reactive-microservices-in-java.pdf.)
 
 Also, you can find the book inside **resources** folder.
 
 
 To run the message base microservices, follow the next steps:
 
##Server message base:
 1) cd hello-microservice-message
 2) mvn compile vertx:run -Dvertx.runArgs="-cluster -Djava.net.preferIPv4Stack=true"

##Client message base:
 1) cd hello-consumer-microservice-message
 2) mvn compile vertx:run -Dvertx.runArgs="-cluster -Djava.net.preferIPv4Stack=true"