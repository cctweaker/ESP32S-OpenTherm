OpenTherm compatible hardware for home automation. It includes all the hardware needed for OpenTherm communication.
Based on the ESP32-S module with external WiFi antenna. Simply connect to OT terminals and power.

You are free to choose the software as there are a few possibilities here:
- ESPHome - OpenTherm is officialy integrated since 2024.11
- Tasmota - more info here: https://tasmota.github.io/docs/OpenTherm/
- build your own local webserver on the ESP using this great library: https://github.com/ihormelnyk/opentherm_library/

The PCB has solder bridges on the back side to select for IN (read/TX) pin GPIO 22 or GPIO 26 and for OUT (write/TX) pin GPIO 21 or GPIO 25.
