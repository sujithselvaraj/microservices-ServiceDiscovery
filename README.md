# microservices-ServiceDiscovery

Before this repository ,Refer to the https://github.com/sujithselvaraj/microservices-connect-demo 
and build the 2 services customer and fraud and connect with the rest template in the customerservice class 


And By this project we can add the eurekaserver and hit the http://localhost:8761 for the express view in the local web browser and make the changes in the application.yml in 
both customer and fraud and change the rest template in the customerconfig and also change the customerservice localhost link 


After doing all this make sure that you have running all the 3 services in the local machine 

Also we can create a another port for the customer 8085 to listen the eureka server in the round robin manner

Here i am using the intelliji ide so i have configured the fraus application 2 in the edit configuration ,So do accordingly to  your machine and make sure that you have enter the program arguments --server.port=8085 to listen in 8085 and append run this application


And hit the postman with http://localhost:8080/api/v1/customers and check for the logs in fraudapplication and fraudApplication2
