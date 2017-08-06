# Source code on-board electronics

Still need to acquire some electronics modules, so can't start programming until then.

Planned testing phases are as follows:

## Phase 1

**Hardware required:**
1. Arduino
2. Raspberry Pi
3. Raspberry Pi Camera Module
4. Motion Sensor (IMU)

**Goals:**
1. Establish a serial communication line between the Arduino and the Pi.
2. Create scripts to control the Pi's Camera.
3. Transmit data from the IMU to the Arduino to the Pi to an external PC.
4. Use the motion sensor data to create a 3 dimensional visualization of the orientation and position of the "body".

## Phase 2

**Hardware required:**
1. Everything in Phase 1
2. GPS Module

**Goals:**
1. Everything in Phase 1
2. Plot the "body's" position on a digital map with the GPS module data.
3. Use the motion sensor data and combine it with the GPS module data to create a 3 dimensional GPS visualizer.

## Phase 3

**Hardware required:**
1. Everything in Phase 2
2. The battery
3. A canister to store everything in (probably have to custom create it)
4. Vehicular Suspension-like spring (probably have to custom create it)

**Goals:**
1. Everything in Phase 2.
2. Make the entire system independent by connecting the system to it's own power supply (i.e., the battery).
3. Test the canister (with dummy weights to account for the electronics), mount it on the "suspension", and test it under simulated flight conditions.
3. Place the system in the canister and run tests.

## Phase 4

**Hardware required:**
1. Everything in Phase 3
2. Communications Module

**Goals:**
1. Everything in Phase 3.
2. Add and link up the system to the communications module.
3. Test remote data transfer (to and from the system).
4. Test communications strength at long ranges (applicable if using Radio Frequency communications).
