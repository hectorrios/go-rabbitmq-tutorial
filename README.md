# TutorialEdge.net RabbitMQ tutorial

YouTube video can be found here: 
https://www.youtube.com/watch?v=pAXp6o-zWS4&list=PLzUGFf4GhXBL4GHXVcMMvzgtO8-WEJIoY&index=29&t=0s

The Docker command to start up the RabbitMQ container is:
> docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management

## Message Producer

To run the message producer, execute the following:

> go run main.go

## Message Consumer

To run the message consumer, execute the following:

> go run consumer.go
