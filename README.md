
# Athom configs are only applicable to ESP8285,[Please click for ESP32 devices](https://github.com/athom-tech/esp32-configs)
### Athom ESPHome configurations
This repository contains a bunch of ESPHome configurations for https://athom.tech devices.
If you are prompted that there is not enough space, you should upgrade `ESP8266_MINI.bin` first

- mini is a transit firmware, after running, it will generate a hotspot of "ESP_UPDATE_XXXXXX"
- Connect to the hotspot and visit `http://192.168.4.1/update` in the browser
- Upload updated ESPHome firmware

### Device List
device|picture|file name|notice
:---:|:---:|:---:|:---:
Athom_Plug_V2|<img src="https://github.com/athom-tech/athom-configs/blob/main/images/Athom_EU_Plug_V2.png" width="50%" height="20%">|athom-smart-plug-v2.yaml
Athom_Wall_Outlet|<img src="https://github.com/athom-tech/athom-configs/blob/main/images/Athom_Wall_Outlet.png" width="50%" height="20%">|athom-wall-outlet.yaml
Athom_Garage_Door_Opener|<img src="https://github.com/athom-tech/athom-configs/blob/main/images/Athom_Garage_Door_Opener.png" width="50%" height="20%">|athom-garage-door.yaml
