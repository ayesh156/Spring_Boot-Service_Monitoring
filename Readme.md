# First Start the Kafka environment

## Run the following commands in order to start all services in the correct order:
### Start the ZooKeeper service
bin/zookeeper-server-start.sh config/zookeeper.properties

## Open another terminal session and run:
### Start the Kafka broker service
bin/kafka-server-start.sh config/server.properties

## Download Keycloak
Download and extract keycloak-25.0.2.zip from the Keycloak website.

### Start Keycloak
bin\kc.bat start-dev