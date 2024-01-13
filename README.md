<h1>Transforming Static Data into a Live Notification System with Python, Kafka, and ksqlDB</h1>

<p>Explore the world of live notifications by building a dynamic system that transforms static data into real-time updates. <br>
This project leverages Python, Kafka, and ksqlDB to bring data to life, with a focus on YouTube's REST API as a static data source.</p>

1. <strong>Getting Started:</strong> Clone the Repository

2. <strong>Set Up Dependencies:</strong> Ensure you have Python installed on your machine.

3. <strong>Install required Python packages:</strong> pip install -r requirements.txt

4. <strong>Configure API Keys:</strong> Obtain API keys for YouTube, Kafka, and Telegram. Configure these keys in the project.

5. <strong>Setting Up the Environment:</strong> Create Kafka Cluster, Set up a Kafka cluster in Confluent Cloud to act as the central data streaming platform.

6. <strong>Create ksqlDB Cluster:</strong> Establish a ksqlDB cluster in Confluent Cloud to process and analyze data with SQL-like queries.

7. <strong>Schema Registry:</strong> Deploy a separate cluster for Schema Registry to manage schema evolution and compatibility.

8. <strong>Data Processing and Streaming:</strong> Define and execute ksqlDB queries to process incoming data, identify important changes, and generate alerts.

9. <strong>API Endpoint Configuration:</strong> Configure API endpoints for YouTube's REST API to fetch and process static data.

10. <strong>HTTPS Connection Setup:</strong> Establish a secure HTTPS connection for data transmission between your application and external APIs.

11. <strong>Configuration Setup:</strong> Configure the application with necessary credentials, API keys, and connection details for Confluent Cloud and other services.

12. <strong>Running the Application:</strong> Execute the main application (youtube_watcher.py) to initiate the data fetching, processing, and streaming into Confluent Cloud.

13. <strong>Monitor ksqlDB Output:</strong> Monitor the output of ksqlDB queries to observe real-time changes and updates based on the processed data.

14. <strong>Telegram Bot Integration:</strong> Set up a Telegram bot and configure the application to push live, custom notifications to Telegram based on the identified changes.

15. <strong>Observing Transformations:</strong> Observe and analyze how the static data from YouTube's REST API transforms into real-time alerts and notifications through the entire pipeline.
