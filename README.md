# Sample ESPHome configuration file for 24GHz mmWave Sensor - Human Static Presence Module Lite (MR24HPC1). 

This respository is for someone who, like me, is trying to get the 24GHz mmWave Sensor - Human Static Presence Module Lite (MR24HPC1) work. I found little or no documentation that would work out of the box.

YMMV.


## Connection
The device is connected to Wemos D1 Mini over software serial with D2 (GPIO4) as RX and D1 (GPIOO5) as TX. So you connect TX pin of MR24HPC1 to D2 / GPIO4 of Wemos D1 Mini and RX pin of MR24HPC1 to D1 / GPIO5 of Wemos D1 Mini.

## Configuration
The default configurations are useless. Please use Custom mode. You'll have to do trial and error.

![image](https://github.com/user-attachments/assets/330963a9-a36e-41f9-a6ae-131d1524f1f7)



*Please note that device is extremely sensitive and will be affected by a fan or AC. Point it away from both. Reduction in sensitivity may not work.*


