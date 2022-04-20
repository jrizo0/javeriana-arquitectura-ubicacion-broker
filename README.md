##### Run Mosquitto MQTT

.\mosquitto.exe -v -c .\broker.conf

##### Sub to topic

.\mosquitto_sub.exe -t myTopic -u admin -P 1234

##### Pug to topic

.\mosquitto_pub.exe -t myTopic -m "hello world" -u admin -P 1234
