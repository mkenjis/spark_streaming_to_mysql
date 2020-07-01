# spark_streaming_to_mysql
spark streaming to insert into mysql table

# urpose:
- use kafka to implement producer to be used by spark streaming.
- feed data coming from kafka and insert into mysql table.

# Requirements:
- Spark installed
- Kafka library installled
- Mysql installed
- Table df_aux created

# Objective :
- use kakfa producer to generate input data to be consumed be spark streaming.
- implement some logic inside the spark to consume data from kakfa, process data, and insert results into mysql table.