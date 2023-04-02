# Awesome STM32 HAL

This is a collection of drivers and utilities designed for the STM32 microcontroller series based on the STM32 HAL (Hardware Abstraction Layer) library. You are welcome to contribute to this list by adding awesome implementations through a pull request.

:warning:Please note that these libraries have not been verified and may require porting to your own hardware.



## Sensor
- [BMP180](https://github.com/eepj/BMP180_for_STM32_HAL) / [BMP280](https://github.com/ciastkolog/BMP280_STM32): Digital temperature and pressure sensor
- [MPU6050](https://github.com/leech001/MPU6050) : gyroscope and accelerometer sensor with a total of 6 axes
- [MPU9250](https://github.com/MarkSherstan/STM32-MPU6050-MPU9250-I2C-SPI) / [ICM-20948](https://github.com/therealwokewok/ICM20948) : gyroscope, accelerometer, and magnetometer sensor with a total of 9 axes
- [MLX90614](https://github.com/dinamitemic/mlx90614) :non-contact infrared temperature sensor. Another implementation is also available [here](https://github.com/nimaltd/MLX90614)
- [SHT2X](https://github.com/eepj/SHT2x_for_STM32_HAL) / [SHT3X](https://github.com/henriheimann/stm32-hal-sht3x) : digital temperature and humidity sensors
- SHT4X : Dhe newest digital temperature and humidity sensor. There is no exact implementation for STM32 HAL, but [this implementation](https://github.com/Sensirion/embedded-i2c-sht4x/blob/master/sensirion_i2c_hal.c) can be used as a backbone for implementation.
- [INA226](https://github.com/Autofoxsys/AutoFox_INA226) : Voltage, current and power measurement IC
- [TMP75](https://github.com/ignacioinda/TMP75_STM32_HAL) : Board mount temperature sensor 
- [MCP9803](https://github.com/SimpleMethod/STM32-MCP9803) : Digital temperature sensor
- [VL53L0X](https://github.com/lamik/VL53L0X_API_STM32_HAL) : ToF (Time of Flight) distance measurement sensor


## Analog
- [ADS1115](https://github.com/MrHause/ADS1115_Library) : 16-bit 4 channel i2c analog-to-digital converter ic
- [MCP4725](https://github.com/SMotlaq/mcp4725) : 12bit i2c digital-to-analog converter ic


## IO
- [PCA9685](https://github.com/henriheimann/stm32-hal-pca9685) : 12-bit pwm driver
- [PCF8574](https://github.com/ng91/PCF8574-C-Driver-for-STM32) : 16-bit digital io expander
- [SI5351A](https://github.com/afiskon/stm32-si5351) : I2C based frequency generator


## Display
- [SSD1306](https://github.com/afiskon/stm32-ssd1306) : An OLED display having i2c and spi interface. This library is also compatible with SH1106, SH1107, SSD1309
- [ST7735](https://github.com/afiskon/stm32-st7735) : A TFT LCD display driver
- [SSD1351](https://github.com/afiskon/stm32-ssd1351) : A Color OLED display
- [ili9341](https://github.com/afiskon/stm32-ili9341) : A TFT LCD display with touchscreen feature

## Communication protocol 
- EtherCAT slave : There is an [example](https://github.com/kubabuda/ecat_servo/tree/main/examples/SOES_LAN9252) using LAN9252 hardware
- Modbus : There is [freertos required implementation](https://github.com/alejoseb/Modbus-STM32-HAL-FreeRTOS) which supports RTU/TCP and, [freemodbus port implementation](https://github.com/eziya/STM32_HAL_FREEMODBUS_RTU) that freertos is not mandatory. [PyModbus](https://github.com/pymodbus-dev/pymodbus) would be great option to test modbus hardware.
- [min](https://github.com/min-protocol/min) : Serial communication protocol across microcontrollers which bundle python listener.

## Contributions

Please feel free to contribute to this repository by submitting a pull request with your awesome implementation. However, note that these libraries have not been verified and may require porting to your own hardware.

