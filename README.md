# stm32_bluepill_Programming_with_Arduino_IDE
upload maple bootloader into stm32 bluepill and use Arduino IDE for programming

watch this video for uploading maple bootloader into stm32 blue pill

stm32 bluepill Maple bootloader

https://github.com/rogerclarkmelbourne/STM32duino-bootloader/blob/master/binaries/generic_boot20_pc13.bin

board Manager for Arduino IDE

https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json

**** use Maple DFU bootloader 2.0 option in the "upload method" present in the Arduino IDE.

if stm32 bluepill fails to reset automatically during program upload, then set jumper pin 1(close to the reset switch) for automatic bluepill reset during file upload.
