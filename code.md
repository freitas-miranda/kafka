# Apache Kafka: Mensageria e Stream de dados

## Acessar o controle center
http://localhost:9021/

## Acessar o container do kafka
docker compose exec kafka bash

## Consumir mensagens produzidas a partir do momento que o consumer subir
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=sales

## Consumir mensagens já gravadas (desde o inicio)
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=sales --from-beginning
