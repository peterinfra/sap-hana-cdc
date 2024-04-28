# sap-hana-cdc

Using info from https://github.com/SAP/kafka-connect-sap 

This is an example to sync data from SAP HANA database to a MySQL store. This leverages Debezium to capture the Change data capture flow from SAP Hana and writes them back to SAP HANA and to MySQL. With Data in Kafka and MySQL one can perform additional transformation on the data. 

SAP HANA -> Debezium -> Kafka -> Debezium -> MySQL | SAP HANA

