# Tugas-8-Avro
Buatlah avro producer dan avro consumer seperti contoh pada code yang telah dishare tetapi menggunakan dataset bitcoin_price_Training.

## Prerequisite
1. Install Avro in Python 3
   `pip install avro-python3`
2. Install Requests Package 
   `pip install requests`
3. Install Confluent Kafka Package
   `pip install confluent-kafka`
   
## How to Run
1. Activate Docker and start running `docker-compose.yml` with command
   `docker-compose build`
   `docker-compose up`
2. Running Producer with command `python3 roducer.py`
3. Running Consumer with command `python3 consumer.py`
