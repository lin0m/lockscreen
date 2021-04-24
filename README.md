# lockscreen
This is my final project from "Digital Design Using Verilog". Throughout the year I designed
an embedded SoC with general purpose I/O using Sytem Verilog as well as hardware drivers using C++.
For my final project I created a C program that utilized the general purpose I/O and drivers. 

My project implements a mobile phone lockscreen. The screen displays the temperature and has a 
dynamic background with moving bubbles.The lockscreen is unlocked by entering a password. 


The bubbles are contolled by the FPGA's accelerometer which is communicating to an I/O port using SPI.
The temperature is retreived from the FPGA's temperature sensor which communicates to a port using i2c.
The password is input via a keyboard connected to a I/O port using PS2. The display is connected using VGA
and is controlled by the video subsystem. The bubble sprites are saved in the FPGA's block RAM.
