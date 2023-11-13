If you prefer to use MQTT instead of ESPHome then check this - https://github.com/e6on/ESP32_MiFlora_MQTT

# ESP32_MiFlora_ESPHome
ESP32 BLE client for XIaomi Mi Flora Plant sensors using ESPHome.

ESPHome config for ESP32 to monitor XIaomi Mi Flora Plant sensors. ESP32 can be powered with LiPo battery and battery level is read from ADC pin. Home Assistant can directly read ESP32 battery level and Mi Flora sensor measurements without the need of MQTT server.

## Hardware & Software used

- Adafruit HUZZAH32 – ESP32 Feather Board - https://www.adafruit.com/product/3405
- Adafruit Lithium Ion Battery 3.7v 2000mAh - https://www.adafruit.com/product/2011
- Xiaomi Mi Plant Sensor
- ESPHome: Home Assistant ESPHome add-on - https://esphome.io

## Home Assistant screenshots
![MiFlora](/miflora.png)
![ESP32](/esp32.png)
