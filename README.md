# jacobm/rabbitmq
Simple test setup of RabbitMq with guest/guest user login allowed outside of localhost.

## Usage

To build jacmb/rabbitmq:

docker build -t jacobm/rabbitmq .

## Run RabbitMQ

Run the following command to start rabbitmq:

docker run -d -p 5672:5672 -p 15672:15672 jacobm/rabbitmq
