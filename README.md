# remote-solar-tracker
Simulink models for the distance learning how to video for Simulink deployment to MKR1000 solar tracker with variant subsystems

### Video

Watch the [video](https://www.youtube.com/watch?v=57GxzjSaKhA&feature=youtu.be)

### SolarTrackerSimulationModel.slx 
Simulink model to simulate a solar tracker controlled by settings read from a ThingSpeak channel.  This model also writes the simulated data to a different ThingSpeak channel.
![App Screen Shot](https://github.com/thingspeak/remote-solar-tracker/blob/master/SimModel.png)



### SolarTrackerHardwareModel.slx
The hardware deployment model, the hardware used here is an Arduino MKR1000
![App Screen Shot](https://github.com/thingspeak/remote-solar-tracker/blob/master/HWModel.png)


### SolarTrackerVariantSubsystems.slx
This model contains both the simulation and hardware deployment models, selectable by clicking the desired block at the top level.
![App Screen Shot](https://github.com/thingspeak/remote-solar-tracker/blob/master/VariantModel.png)


### Built With
Simulink

### Authors
* Christopher Stapels - Hardware deployment model
* Deepak Bhatia - Simulation and Variant subsystem models

### Resources
* [ThingSpeak for IoT Projects](https://thingspeak.com)
* [Simulink](https://www.mathworks.com/products/simulink.html)
