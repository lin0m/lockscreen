# lockscreen
One of several projects designed utilizing the embedded SOC from "Digital Design Using Verilog". 
Project implemented on a Nexys 4 DDR FPGA. The lockscreen displays the temperature and some 
bubbles controlled by the accelerometer. Each bubble moves at a different speed. The lockscreen 
is unlocked by entering a password. 

The SOC communicates with the accelerometer using SPI, the temperature sensor using i2c, and 
the keyboard using PS2. The display is connecred using VGA. 
