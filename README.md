# DIY Geiger Counter Module GGreg20_V3

![DIY Geiger counter GGreg20_V3 with J305 pr SBM20 GM-tubes](DIY_Geiger_counter_GGreg20_V3_repo_GitHub_ENG.jpg)
## Easy Links
### Unique Vendor ID
[go.iot-devices.com.ua/ggreg20_v3](https://go.iot-devices.com.ua/ggreg20_v3)
### User Friendly ID
[go.iot-devices.com.ua/geiger-counter](https://go.iot-devices.com.ua/geiger-counter)
### Related Radiation Detection Applications Links:
[go.iot-devices.com.ua/high-voltage-converter](https://go.iot-devices.com.ua/high-voltage-converter) <=>
[go.iot-devices.com.ua/dcdc_3v3_400v_v1](https://go.iot-devices.com.ua/dcdc_3v3_400v_v1)

[go.iot-devices.com.ua/geiger-counter-emulator](https://go.iot-devices.com.ua/geiger-counter-emulator) <=>
[go.iot-devices.com.ua/gcemu20_v1](https://go.iot-devices.com.ua/gcemu20_v1)

## Media coverage
- [Tom's Hardware: Raspberry Pi Radiation Monitor Goes Wireless With Pico W by Ash Hill](https://www.tomshardware.com/news/raspberry-pi-radiation-monitor-goes-wireless-with-pico-w)
- [Tindie Blog: Ionizing Radiation Detector For Safer Foraging by Jo Hinchliffe](https://blog.tindie.com/2021/06/ionizing-radiation-detector-for-safer-foraging/)
- [alterstrategy.lab: Connecting the GGreg20_V3 radiation sensor to the Home Assistant server through ESP Home integration](https://alterstrategy.com/2021/07/20/pidklyuchennya-sensora-radiatsiyi-ggreg20_v3-do-servera-home-assistant-cherez-integratsiyu-esp-home/)

## Hardware compatibility
| MCU | Compatibility | We tested | Code Example |
| ----------------- | ----------------- | ----------------- | ----------------- |
| Raspberry Pi Pico W | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [View it](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#raspberry-pi-pico-w-example--yaml)|
| Arduino UNO | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [View it](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#arduino--c)|
| ESP8266-12F | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [ESPHome / YAML](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#esp8266-example--yaml) and [NodeMCU / Lua](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#nodemcu--lua)|
| ESP32 (generic) | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [ESPHome / YAML](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#esp32-example--yaml) and [Tsmota32 / Berry](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#tasmota--berry)|
| STM32 | :heavy_check_mark: | :x: | :x: |

## Driver Libraries and Code Examples

| IoT Platform | Platform support | We Tested | Code Example |
| ------------- | ------------- | ------------- | ------------- |
| Arduino / C++ | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [View it](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#arduino--c) |
| ESPHome / YAML | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [View it](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#home-assistant-and-esphome) |
| ThingSpeak / REST | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [View it](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#thingspeak--rest)|
| Tasmota / Berry | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [View it](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#tasmota--berry)|
| NodeMCU / Lua | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: [View it](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3#nodemcu--lua)|
| MicroPython | :heavy_check_mark: | :x: | :x: | 

### GGreg20_V3 compatible firmware for Flipper Zero
> If GGreg20_V3 is used with a J305 Geiger tube, no changes are required at all, i.e. you can simply compile this example. 
In other cases (for example, if GGreg20_V3 is used with an SBM20 tube), you need to change the conversion factor for the tube from 0.0081 to the appropriate one (for SBM20 - 0.0057) before compiling the firmware in the source code of this example.

[flipperzero-geigercounter](https://github.com/nmrr/flipperzero-geigercounter)

### Arduino / C++
[IoT-devices GGreg20_V3 Arduino Driver Library](https://github.com/iotdevicesdev/GGreg20_V3)

[Reference Libraries at arduino.cc](https://reference.arduino.cc/reference/en/libraries/ggreg20_v3/)

### Home Assistant and ESPHome
#### ESPHome Devices
[GGreg20_V3 page at devices.esphome.io](https://devices.esphome.io/devices/IoT-devices-GGreg20-V3)
#### ESP8266 Example / YAML
[GGreg20_V3 under Home Assistant with ESPHome setup example](https://github.com/iotdevicesdev/ggreg20-v3-homeassistant-esphome-example#ggreg20_v3-under-home-assistant-with-esphome-setup-example)
#### ESP32 Example / YAML
[GGreg20_V3 with generic ESP32 under Home Assistant with ESPHome setup example](https://github.com/iotdevicesdev/GGreg20_V3-ESP32-HomeAssistant-ESPHome#ggreg20_v3-with-generic-esp32-under-home-assistant-with-esphome-setup-example)
#### Raspberry Pi Pico W Example / YAML
[Raspberry Pi Pico W Geiger counter using GGreg20_V3 and ESPHome example](https://github.com/iotdevicesdev/RPi-Pico-W_GGreg20_V3-ESPHome)

### ThingSpeak / REST
[GGreg20_V3 Radiation Sensor Node with ThingSpeak REST-API for Home Assistant](https://github.com/iotdevicesdev/GGreg20_V3-Kyiv-Radiation-Sensor-ThingSpeak-HomeAssistant#ggreg20_v3-radiation-sensor-node-with-thingspeak-rest-api-for-home-assistant)
### Tasmota / Berry
[GGreg20_V3 and ESP32 Tasmota Firmware driver](https://github.com/iotdevicesdev/ggreg20-v3-tasmota-esp32-driver#ggreg20_v3-and-esp32-tasmota-firmware-driver)

[Tasmota Supported Peripherals](https://tasmota.github.io/docs/Supported-Peripherals/)

### NodeMCU / Lua
[GGreg20_V3 NodeMCU firmware Lua code example](https://github.com/iotdevicesdev/ggreg20-v3-nodemcu-lua-example#ggreg20_v3-nodemcu-firmware-lua-code-example)
### Wokwi / C++
[GGreg20_V3 radiation counter simulator for Arduino UNO powered by WOKWI](https://github.com/iotdevicesdev/ggreg20-v3-arduino-uno-wokwi-simulator#ggreg20_v3-radiation-counter-simulator-for-arduino-uno-powered-by-wokwi)

## Some examples of GGreg20_V3 use cases
### GMCMap - Geiger counter World map
#### Czech Republic 
##### Plzen [Jump to it](https://www.gmcmap.com/historyData.asp?Param_ID=46638764351)
![gmc_map_Plzen_CzechRepublic_GGreg20_V3_SBM20_2023-07-12_230957](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/061bef73-f14d-4d5a-9185-b8aca04db5e1)

#### France
##### Lyon (Sensor 1) [Jump to it](https://www.gmcmap.com/historyData.asp?Param_ID=79913303488)
![gmcmap_diy_ggreg30_v3_lyon1_2023-07-16_164541](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/e18f2dea-bcbf-47b5-9d80-986179ccc76e)

##### Lyon (Sensor 2) [Jump to it](https://www.gmcmap.com/historyData.asp?Param_ID=81743704750)
![gmcmap_diy_ggreg30_v3_lyon2_2023-07-16_164541](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/128ae689-85fa-4ed9-b3b8-856d0383311d)

#### Ukraine 
##### Kyiv (demo-mode) [Jump to it](https://www.gmcmap.com/historyData.asp?Param_ID=18247516329)
![MAP_GGreg20_V3_SBM20_Screen_2023-07-14_153420_2](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/03979abc-2576-4c1a-b4dc-6fdcaba32b44)

### ThingSpeak
[Jump to it](https://thingspeak.com/channels/1749073)
![ThingSpeak_iot-devices_Kyiv_2023-07-10_175726](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/bdf68991-1d12-4742-850f-5ad05fa388e2)

### Radmon.org
[Jump to it](https://radmon.org/radmon.php?function=showuserpage&user=jardous)
![Domstadt_jardous_2023-07-10_174204](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/5cabf96c-03af-48c6-a0f1-61e0df01d559)

[Jump to it](https://radmon.org/radmon.php?function=showuserpage&user=htotoo)
![Hungary_Budapest_htotoo_2023-07-10_172950](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/fdf28739-b02d-41fd-b8ad-275591a7a628)

[Jump to it](https://www.reddit.com/r/raspberry_pi/comments/14kw5ur/remote_wifi_radiation_monitor_using_rpi_pico_w/)
![RPi_Sboger_reddit_2023-07-10_180802](https://github.com/iotdevicesdev/DIY-Geiger-Counter-Module-GGreg20_V3/assets/96241971/a45bedb4-734f-46b0-ad7b-4a8e324470e6)

## Technical Notes
[Technical note on voltage level matching for GGreg20_V3 and 5V MCU](https://iot-devices.com.ua/en/technical-note-on-voltage-level-matching-for-ggreg20v3-and-5v-mcu/)

[DIY Geiger counter: GGreg20_V3 and ESP12.OLED connection diagram](https://iot-devices.com.ua/en/diy_geiger_counter_ggreg20_v3_and_esp12-oled_wiring_diagram_en/)

[Geiger counter GGreg20_V3: maximum radiation that can be measured](https://iot-devices.com.ua/en/maximum-radiation-that-can-be-measured-by-geiger-counter-ggreg20_v3-en/)

[Geiger counter GGreg20_V3: supply voltage range of the Geiger counter module](https://iot-devices.com.ua/en/technical_note_supply_voltage_range_geiger_counter_ggreg20_v3/)

[Technical note on bug fixes in ESPHome firmware for ESP32 regarding GPIO and interrupt handler settings modes](https://iot-devices.com.ua/en/technical-note-on-esp32-gpio-interrupt-esphome-bug-fixes/)

[Technical note: Geiger counter at low temperatures – the work of a DIY module](https://iot-devices.com.ua/en/technical_note_performance_of_diy_geiger_counter_ggreg20_v3_at_low_-temperatures/)

[UV test of Geiger tubes J305](https://iot-devices.com.ua/en/uv-test-of-the-j305-geiger-tubes/)

[Technical note: How to calculate the conversion factor for Geiger tube SBM20](https://iot-devices.com.ua/en/technical-note-how-to-calculate-the-conversion-factor-for-geiger-tube-sbm20/)

[Geiger-Muller tubes: Comparison of SBM20, J305 and LND712](https://iot-devices.com.ua/en/comparison-of-geiger-muller-tubes-sbm20-j305-and-lnd712/)

## Projects
### Online services where GGreg20_V3 is present
[gmcmap.com](https://gmcmap.com)

[radmon.org](https://radmon.org)

[thingspeak.com](https://thingspeak.com/channels/public?tag=geiger)

### Tags and Topics
[Hackaday GGreg20_V3 tag](https://hackaday.io/projects?tag=ggreg20_v3)

[GitHub GGreg20_V3 topic](https://github.com/search?q=topic%3Aggreg20-v3&type=repositories)

[Hackaday 'Geiger Counter' tag](https://hackaday.io/projects?tag=Geiger%20counter)

[GitHub 'geiger-counter' topic](https://github.com/search?q=topic%3Ageiger-counter&type=repositories)

[Medium 'Geiger Counter' tag](https://medium.com/tag/ggreg20-v3)

[HackerNoon 'Geiger Counter' tag](https://hackernoon.com/tagged/ggreg20_v3)

### Search
[Hackaday GGreg20_V3 search](https://hackaday.io/search?term=ggreg20_v3)

[Instructables GGreg20_V3 search](https://www.instructables.com/search/?q=ggreg20_v3&projects=all)

[Tindie Blog GGreg20_V3 search](https://blog.tindie.com/?s=GGreg20_V3)

[IFIXIT GGreg20_V3 search](https://www.ifixit.com/Search?query=ggreg20_v3)

