# MensageriaMassTransit

Solução de exemplo de Mensageria usando MassTransit e RabbitMQ.

Para rodar um servidor para troca de mensagens:

docker run -p 15672:15672 -p 5672:5672 masstransit/rabbitmq
