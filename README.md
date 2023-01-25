# application-emp
prerequisite:-
You need a MYSQL database, with "emp" database inside it, rest all the tables and data will be automatically created by the java code using hibernate.

query to create database inside MYSQL:-
create database emp;

backend endpoint Example- http://localhost:8080/api/v1/employees

Env variables:- ENDPOINT=<database_endpoint> USER=<database_user> PASSWORD=<database_password>

docker hub image link - https://hub.docker.com/repository/docker/zabakar/javabackend/general

backend endpoint example - http://localhost:8080/api/v1/employees

docker command to run container example - docker run -itd -p 8089:8089 -eENDPOINT=database-2.czg5d44n2tyl.us-east-1.rds.amazonaws.com -eUSER=admin -ePASSWORD=password zabakar/javabackend:v3

URL to check the backend example - http://44.203.155.140:8089/api/v1/employees - here the IP should be your's, you should see [ ], because there is no data in the database


