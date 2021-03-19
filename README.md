# RabbitMQ-demo
Working with RabbitMQ Message broker using dotnetcore

two console apps , producer and consumer communicating with rabbitMQ

using various queues and exchanges (direct, topic, header ,  fanout)

RabbitMQ is installed in a linux docker container with following command 

"docker run -d --hostname my-rabbit --name demo-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management"



