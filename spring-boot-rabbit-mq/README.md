# spring-boot-rabbit-mq
RabbitMQ con Spring Boot
1) crearemos una imagen de rabbitmq en nuestro docker local:
   docker run -d --restart always --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management
2) luego de que esta instalada y ejecutandose vamos a nuestro navegador y cargamos la consola de rabbitmq:
   http://localhost:5672/
   usr:guest
   psw:guest

referencia:
https://www.youtube.com/watch?v=IdJ3bS-7cbg&t=674s

