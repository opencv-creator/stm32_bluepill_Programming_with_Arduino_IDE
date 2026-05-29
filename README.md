# stm32_bluepill_Programming_with_Arduino_IDE
upload maple bootloader into stm32 bluepill and use Arduino IDE for programming

watch this video for uploading maple bootloader into stm32 blue pill

stm32 bluepill Maple bootloader

https://github.com/rogerclarkmelbourne/STM32duino-bootloader/blob/master/binaries/generic_boot20_pc13.bin

board Manager for Arduino IDE

https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json

**** use Maple DFU bootloader 2.0 option in the "upload method" present in the Arduino IDE.

if stm32 bluepill fails to reset automatically during program upload, then set jumper pin 1(close to the reset switch) for automatic bluepill reset during file upload. 
the sample picture for this setting is present in this repository.


----------------------------------------------------------------------------------------------------------------------------------

proteus simulation with code compiled using stm32cubeide 1.12.1 and arduino ide 2.0.3

get arduino ide from the below link

https://github.com/arduino/arduino-ide/releases?page=2

install stm32 blue pill board using the below board manager link in arduino ide preferences

https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json

for the Board selection in Arduino IDE -- > STM32 MCU Based Boards --- > choose Generic STM32F1 series 
for board Part Number ---> Generic F103C8TX


