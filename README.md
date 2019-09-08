# Rabbit-MQ
A Messaging System Application


RabbitMQ installation proces
=================================
RabbitMQ written in Erlang programming language. So we need to first install Erlang.

1)install Erlang
2) install RabbitMQ
      after installation, will be able to see RabbitMQ command prompt.
	  
3)install RabbitMQ plug-in for Management console(http:localhost:---)
   fire this command on rabbitMQ command prompt: rabbitmq-plugins enable rabbitmq_management

 Now go to the browser hit: localhost:15672
 
 
 4) Go browser and type  http://localhost:8080/my-rabbitmq/producer?empName=RKumar&empId=rk001  query param.
 
 5) Go to rabbit mq management console by using below link
  http://localhost:15672 and navigate to >> Queues tab >> find exchange name(kumar.exchange)>> and then Get message(s). Here you will get 
  Pushed message payload in the rabbitmq.
  
  Thanks
