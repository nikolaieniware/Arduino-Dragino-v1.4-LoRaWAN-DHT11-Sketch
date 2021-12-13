# Arduino-dragino-v1.4-BG-sketch
Sketch for Adruino UNO plus LoRaWAN Shield Dragino v1.4 + DHT11 sensor for Temperature and Humidity. Also added a flow for Node-Red to visualise the value of Temperature and Humidity.The value is safe in Influxdb database for easier visualisation in Grafana. Authentication metod is ABP for this example.(Not test the OTAA yet). To decode the payload from gateway use the file with decoder for this example. For testing, the node and Gateway are very close each other.

Node-Red Flow:

![Screenshot_1](https://user-images.githubusercontent.com/36404591/145826200-595fe195-9f06-4ad9-abb4-a776e8710db8.png)

Grafana Dashboard:

![Screenshot_3](https://user-images.githubusercontent.com/36404591/145827694-af463c61-f4cd-4cf9-967d-39d4e7fe3153.png)

