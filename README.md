# ESP32NodeSensorOTAUpdate.github.io

## Node Sensor Firmware Update

### **v1.0.0**
- Initial release firmware with feature OTA
- 3 indicator LED (SYS, TX, RX)
- SYS indicate system ready with static LED, when LED blinking SYS not ready
- RX indicate system reading or receiving data sensor
- TX indicate system transmitting data sensor to MQTT broker
- Reset button
- Config file can access by hit http://node-sensor.local/api/config and update using endpoint http://node-sensor.local/api/update/config
