# Arduino-dragino-v1.4-BG-sketch
Sketch for Adruino UNO plus LoRaWAN Shield Dragino v1.4 + DHT11 sensor for Temperature and Humidity. Also added a flow for Node-Red to visualise the value of Temperature and Humidity.The value is safe in Influxdb database for easier visualisation in Grafana. Authentication metod is ABP for this example.(Not test the OTAA yet). To decode the payload from gateway use the file with decoder for this example. For testing, the node and Gateway are very close each other.

Arduino UNO:

![A000066_03 front_934x700](https://user-images.githubusercontent.com/36404591/145829992-924c07de-f9c4-498b-87e1-85c112b58992.jpg)

LoRaWAN Dragino v1.4:

![400px-Lora_Shield_v1 4](https://user-images.githubusercontent.com/36404591/145830061-94a19074-b462-4fa7-9a11-c6894cc92119.jpg)

Sensor for Temperature and Humidity:

![8e1102675_DHT11-Luchtvochtigheid-temperatuur-sensor_x](https://user-images.githubusercontent.com/36404591/145830152-7a775928-618c-4b1e-9eeb-31500aeed4b7.png)


Node-Red Flow:

![Screenshot_1](https://user-images.githubusercontent.com/36404591/145826200-595fe195-9f06-4ad9-abb4-a776e8710db8.png)

Node-Red UI:

![Screenshot_4](https://user-images.githubusercontent.com/36404591/145829667-c0cc2d91-0a7f-4393-a038-cee024d64d20.png)


Grafana Dashboard:

![Screenshot_3](https://user-images.githubusercontent.com/36404591/145827694-af463c61-f4cd-4cf9-967d-39d4e7fe3153.png)

