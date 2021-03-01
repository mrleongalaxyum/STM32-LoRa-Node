# Meteo_senzor
 Repo for PCB design

This is my custom hardware project created as a part of a college project at [Faculty of Electrical Engineering and Computing in Zagreb ](https://www.fer.unizg.hr/en "FER")

The board is based on [STM32L072/L073](https://www.st.com/en/microcontrollers-microprocessors/stm32l073rz.html) and features a [Bosch BME280](https://www.bosch-sensortec.com/products/environmental-sensors/humidity-sensors-bme280/) Temp/Pressure/humidity sensor. The LoRaWAN module is an [SX1276 by RadioControlli](https://www.radiocontrolli.com/rc-sm1276-868). The headers have all the GPIO exposed, except for the SPI1 which is occupied by the LoRa module. Headers are breadboard-friendly and leave 1 row of free breadboard pins at each side of the board.

The PCB is drawn in Altium Designer and all the files are available in the repo


![alt text](https://github.com/mrleongalaxyum/STM32-LoRa-Node/blob/master/pinout.png)
