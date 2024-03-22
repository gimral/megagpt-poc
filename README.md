# megagpt-poc

To run the generation
`
metagpt 'prompt'

1. Inbuilt software company settings
    * Create a flink job that has two Kafka topic inputs, both topics has json structures, it should join the streams using the key fields, after joining it should perform a lookup from a Redis cache and send the output data to a Kafka topic
    * Implement a spark job that will read data from an oracle database in an incremental manner and load the data into HIVE. Make the job as generic as possible to support defining the table name on oracle, column to track incremental loads, target HIVE table. It should also support ingesting into SCD2 based HIVE tables.
    * GPT4: Implement a spark job that will read data from an oracle database in an incremental manner and load the data into HIVE. Make the job as generic as possible to support defining the table name on oracle, column to track incremental loads, target HIVE table. It should also support ingesting into SCD2 based HIVE tables. Implement all the classes as much as possible.
