# Microservice **with Node.js**

- Using Kafka
- Using NodeJS

## Applications

- Main API (Station)
- Certification Generation

## Microservice Flow

- API sends a message to the Certification's Microservice to generate it.
- Certification's Microservice sends back a response (sync/async).
- Receive an async response when a certificate's email was sent.

## What we know until now?

- REST (latency)
- Redis / RabbitMQ / **Kafka**

## Enterprises which use Kafka
- Nubank, Uber, Paypal, and Netflix;

