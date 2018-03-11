# my-first-vertx-app
 my-first-vertx-app 
 
 Sample base on [Dzone Buiding reactive mircroservices Refcard ](https://dzone.com/storage/assets/5465811-building-reactive-microservices-in-java.pdf.)
 
 Also, you can find the book inside **resources** folder.
 
 
 To run the message base microservices, follow the next steps:
 
## Server message base:
``` shell
 foo@bar:~$cd hello-microservice-message
 foo@bar:~$mvn compile vertx:run -Dvertx.runArgs="-cluster -Djava.net.preferIPv4Stack=true"
```

## Client message base:
``` shell
 foo@bar:~$cd hello-consumer-microservice-message
 foo@bar:~$mvn compile vertx:run -Dvertx.runArgs="-cluster -Djava.net.preferIPv4Stack=true"
``` 