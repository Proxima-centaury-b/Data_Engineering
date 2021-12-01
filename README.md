This project is a reminder of the main features of Airflow and Kafka. Use case is toll data, which could be produced by many IoT devices like cameras 
(which register every car passing through the toll for example). Airflow is used to automatize the ETL process from different sources in S3. 
Then we process streaming data with Kafka and load it into a MySQL DB. 
