# AOG bluetooth twin serial autosteer
Autosteer sketch that add a dedicated bluetooth serial and detect which serial connection (USB or bluetooth) is active, so you can use bluetooth or USB, made for V5.2.2.
I used SPI bus pin's on the top of the nano because they are accessible, MOSI and MISO are pin's 11 & 12, there is +5v and GND in the near pin's.

# AOG CMPS14 IMU on ESP32 via bluetooth
Sketch modified from autosteer via USB, it allow to get CMPS14 IMU data (on i2c bus) and send it via bluetooth.
