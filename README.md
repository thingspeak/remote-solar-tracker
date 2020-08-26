# remote-solar-tracker
Simulink models for the distance learning how to video for Simulink deployment to MKR1000 solar tracker with variant subsystems

### Video

Watch the [video](https://www.youtube.com/watch?v=57GxzjSaKhA&feature=youtu.be)

### SolarTrackerSimulationModel.slx
![App Screen Shot](https://github.com/thingspeak/remote-solar-tracker/blob/master/SimModel.png)

Simulink model to simulate a solar tracker controlled by ThingSpeak.  This model writes the simulated data to a different ThingSpeak channel.

### SolarTrackerHardwareModel.slx
![App Screen Shot](https://github.com/thingspeak/remote-solar-tracker/blob/master/HWModel.png)

The hardware deployment model.

### SolarTrackerVariantSubsystems.slx
![App Screen Shot](https://github.com/thingspeak/remote-solar-tracker/blob/master/VariantModel.png)

This model contains both the simulation and hardware deployment models, slectable by clicking the desired block at the top level.

### Built With
Simulink

### Authors
* Christopher Stapels - Hardware deployment model
* Deepak Bhatia - Simulation and Variant subsystem models

### Resources
* [ThingSpeak for IoT Projects](https://thingspeak.com)
* [Simulink](https://www.mathworks.com/products/simulink.html)
