# DisasterComm

A Severity-Aware Big Data Communication Framework for Effective Disaster Notification.
## 📄 Research Paper
You can read the full research paper [here](DisasterComm%20-%20A%20Severity-Aware%20Big%20Data%20Communication%20Framework%20for%20Effective%20Disaster%20Notification%20(1).pdf).


## Overview
This project uses  Kafka, Flink, RabbitMQ, Spark and Hadoop to prioritize and process disaster data in real time.

### Components
High-severity pipeline:
1)Kafka_producer.py
2)Kafka_consumer_Flink.py
Medium-severity pipeline:
1)RabbitMQ_producer.py
2)Pika_intermediate
2)Spark.py
Low-severity pipeline:
1)Disaster_data_generator.py
2)Mapper.py 
3)Reducerfire.py
4)Reducerflood.py
5)Reducerpower.py
