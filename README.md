<h1>Transforming Static Data into a Live Notification System with Python, Kafka, and ksqlDB</h1>

<p>Explore the world of live notifications by building a dynamic system that transforms static data into real-time updates. <br>
This project leverages Python, Kafka, and ksqlDB to bring data to life, with a focus on YouTube's REST API as a static data source.</p>

1. Getting Started: Clone the Repository

2. Set Up Dependencies: Ensure you have Python installed on your machine.

3. Install required Python packages: pip install -r requirements.txt

4. Configure API Keys: Obtain API keys for YouTube, Kafka, and Telegram. Configure these keys in the project.

5. Setting Up the Environment: Create Kafka Cluster, Set up a Kafka cluster in Confluent Cloud to act as the central data streaming platform.

6. Create ksqlDB Cluster: Establish a ksqlDB cluster in Confluent Cloud to process and analyze data with SQL-like queries.

7. Schema Registry: Deploy a separate cluster for Schema Registry to manage schema evolution and compatibility.

8. Data Processing and Streaming: Define and execute ksqlDB queries to process incoming data, identify important changes, and generate alerts.

9. API Endpoint Configuration: Configure API endpoints for YouTube's REST API to fetch and process static data.

10. HTTPS Connection Setup: Establish a secure HTTPS connection for data transmission between your application and external APIs.

11. Configuration Setup: Configure the application with necessary credentials, API keys, and connection details for Confluent Cloud and other services.

12. Running the Application: Execute the main application (youtube_watcher.py) to initiate the data fetching, processing, and streaming into Confluent Cloud.

13. Monitor ksqlDB Output: Monitor the output of ksqlDB queries to observe real-time changes and updates based on the processed data.

14. Telegram Bot Integration: Set up a Telegram bot and configure the application to push live, custom notifications to Telegram based on the identified changes.

15. Observing Transformations: Observe and analyze how the static data from YouTube's REST API transforms into real-time alerts and notifications through the entire pipeline.
