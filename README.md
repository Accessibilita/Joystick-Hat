# Joystick-Hat
RPi Hat for controlling an open source wheel chair! This hat contains all the necessary electronics for interfacing and powering all the components/peripherals that will be used to control the open source wheel chair electrical system we are developing with the Accessibilita project !!

Quick Specs of the Hat:
- STM32F446RET6 100TQFP ARM Cortex M4 Microcontoller
- ARM Cortex M Serial Debu Interface/connector for in system programming and development 
- MAX3535ECWI+T RS485 Transceiver for communicating with main motor controller
- D24V22F5 2.5A 5VDC Voltage Regulator Module
- D24V22F3 2.5A 3.3VDC Voltage Regulator Module
- D24V22F12 2.5A 12VDC Voltage Regulator Module
- 24V Power Input with High Current Pheonix Contact Connector
- 12V Power output with High current Phoenix Contact Connector
- Rapsberry Pi 5 Running ROS2, directly power via header from 5VDC rail
- 8 Debug LEDs for STM32F446RET6
- 8 Debug LEDs for RPi 5
- Onboard Battery for STM32F446RET6 RealTime Clock
- Interface for JoyStick, JH-D202X-R2/R4 Joystick 5K https://protosupplies.com/product/jh-d202x-r2-r4-joystick-5k/
- Interface for two Rotary Switches
- Interface for 8 Momentary swiches/buttons
- Interface for LED driver board, this additional board drives LEDs in the arm wrest indicating battery level and current set speed
- STM32 will run custom FreeRTOS or ROS-Micro more to follow

This hat is intended as a developmental platform that can function in the field, it has all the features needed to control the wheel chair with additional feature that will make software development easier. The final version will be much simpler and low cost, this is only the beginning. 
