# Heart-Monitoring-System
This is a heart-status monitoring system composed of three layers. The first layer is an input layer containing IoT sensors: Galvanic-Skin-Response Sensor, DHT22 Temperature Sensor, DS18B20 Temperature Sensor,  MAX30102 Oximeter, and AD8232 ECG Sensor. An Arduino UNO is connected to these sensors and is used to transmit data to the second layer, a python program that contains a Support Vector Machine Algorithm that's used to predict the patient's heart status. Finally, after the predcition is made, data is transmitted to a Real-Time Firebase Database that shows the data and heart-prediciion on an Android Mobile Application connected to it.
