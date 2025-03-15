# Fake E-commerce Order Stream to Apache Kafka

This project generates fake e-commerce orders and streams them to an Apache Kafka topic using Python. It can be run on Google Colab or locally.

## Features
- Generates random e-commerce orders using the `Faker` library.
- Streams the orders to an Apache Kafka topic.
- Provides a Kafka consumer to read and verify the messages.
- Supports SSL authentication for secure Kafka clusters.

## Setup & Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/fake-ecommerce-orders-kafka.git
   cd fake-ecommerce-orders-kafka
