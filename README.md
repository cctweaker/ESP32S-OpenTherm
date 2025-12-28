OpenTherm compatible hardware for home automation. It includes all the hardware needed for OpenTherm communication.
Based on the ESP32-S module with external WiFi antenna. Simply connect to OT terminals and power.

You are free to choose the software as there are a few possibilities here:
- ESPHome - OpenTherm is officialy integrated since 2024.11, more info here: https://esphome.io/components/opentherm.html
- Tasmota - more info here: https://tasmota.github.io/docs/OpenTherm/
- build your own local webserver on the ESP using this great library: https://github.com/ihormelnyk/opentherm_library/

The PCB has solder bridges on the back side to select for IN (read/RX) pin GPIO 22 or GPIO 26 and for OUT (write/TX) pin GPIO 21 or GPIO 25.

For Tasmota configure GPIO 25 as OpenTherm TX (203) and GPIO 26 as OpenTherm RX (202).
Example ESPHome configuration yaml is added to the repository.
