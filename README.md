# x86Drone-Hardware
## 1. Main Board

Tentative list of other options in terms of boards will be maintained here. 
As of now, **UDOO x86 II** seems a good fit.
- x86 Intel Pentium CPU
- Compatible with all x86 Linux Distros, as well as Windows
- Natively runs Arduino sketches and libraries, initial hardware testing can be done with already available Arduino Flight Controller Libraries, that should run without much hassles.


## 2. Sensor

Current consideration - **MPU 6050 IMU**
- 3 Axis Accelerometer
- 3 Axis Gyro
- Can be connected using GPIO which is available on the above board 
- Known to work with raspberry pi on linux


## 3. Electronic Speed Controller (ESC)

Any ESC Can be directly connected to the board using GPIO pins
-Tentative Requirements - 30A or above


## 4. Frame 

Bigger frames are recommended online to give more room for DIY flexibility
Current Consideration - 550mm frame


## 5. Motors and Props

Brushless motors used for longer life. 
- Need to achieve a Weight to Thrust Ratio above 1.5 (preferably 2)
- Current Considerations 
* Motors - 2212, 920kV
* Props - 1045



## 6. PDB 

To be decided

## 7. Battery

To be decided

## Interfacing

![Udoo Interface](/udoo_interface.jpg)




