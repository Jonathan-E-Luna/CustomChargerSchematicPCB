# CustomChargerSchematicPCB
During my groups capstone, I was in charge of the PCB design for all custom hardware components utilized. The boards are subdivided into three main catagories
1) Power boards- These boards are Switching Regulators designed to power the microcontronller, Current Switch Board (Will be mentioned later) and a raspberry pi module. Since all power boards use the same switch regulator IC, only one is shown
2) MCU Board - This board houses an ESP-32 Microcontroller that will controll the Current/Voltage measurement IC (INA260) and the Load Switch TPS22918
3) Current Switch Board - Houses the INA260 and TPS22918 that will take current from the 5V regulator and deliver power to a load.
