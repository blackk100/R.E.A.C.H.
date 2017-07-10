<!-- Uses GitHub Flavoured Markdown-->

# R.E.A.C.H. Mk1  Data Sheet

## Reach Beyond

__TGT : Break Aerospace Limit__

__Total Budget: INR 40,000__

## Key

 1. __(?UL) - Indicates that value falls in the higher range of possible values__
 2. __(?LL) - Indicates that value falls in the lower range of possible values__

## Build Materials

 1. ### Structural

	|S No |Part                                          |Projected Cost             |Quantity|Notes                                                    |
	|:---:|:--------------------------------------------:|:-------------------------:|:------:|:--------------------------------------------------------|
	|1    |Hardened Automobile Grade Aluminium Sheet 80mm|INR 500/m<sup>2</sup>      |6       |Fuselage is 0.11 (Radius) x 8 (Height) + 0.25 (Nose Cone)|
	|2    |Stainless Steel Cylinder 0.13m x 0.2m         |INR 1500                   |1       |-                                                        |
	|3    |Rivets / Screws / Assorted Tools              |INR 200                    |DNM     |-                                                        |
	|4    |Compressed Air Tank 15L @ 2 atm               |INR 3400 (?UL)             |1       |Dimensions are Tentative                                 |
	|5    |Lever/Latch Locks                             |INR 250                    |4       |-                                                        |
	|6    |Aluminum/Copper/Plastic/Rubber Tubing 20mm    |INR 500/m (?UL)            |2       |-                                                        |
	|7    |Gas Valves 20mm                               |INR 100                    |2       |Rated for 4 Atm                                          |
	|8    |Servos                                        |INR 300 (?UL)              |4       |For Valve Operation                                      |
	|9    |Shock Absorbant Foam                          |INR 400/m<sup>2</sup> (?UL)|1.5     |Non-Flammable                                            |
	|10   |Telescopic Recovery Fins                      |Custom                     |3       |4.75 + 4.5 + 4.25                                        |
	|11   |PVC Pipe 50mm 5.7m x 0.105m                   |Custom                     |1       |-                                                        |

	_Assorted Adhesives & Tools & Mounts Not Included_

	**Total (?UL) : INR 15,200**

 2. ### Solid Rocket Motor

	|S No |Chemical                         |Projected Cost/KG |Projected Quantity|Notes                                |
	|:---:|:-------------------------------:|:----------------:|:----------------:|:------------------------------------|
	|1    |Laboratory Grade Aluminium Powder|INR 120           |5                 |Main Fuel                            |
	|2    |Paraffin Wax                     |INR 200           |0.5               |Gelling Agent                        |
	|3    |TEMED                            |INR 1000          |0.05              |Will Get From Labs, Stabilizer for OX|
	|4    |Ammonium Persulphate             |INR 100           |86                |OX                                   |
	|5    |Rubber/Resin                     |-                 |Tentative         |Setting Agent                        |

	_Material For Test Fires Not Included_

	**Total (?UL) : INR 11,000**

 3. ### Electronics
	__See [Here](Electronics_List.md)__

	|S No |Part         |Projected Cost|Quantity|Notes           |
	|:---:|:-----------:|:------------:|:------:|:--------------:|
	|1    |9v DC Battery|INR 50/pc     |10      |Vacuum Sensitive|

	**Total (?UL) : INR 10,000**

### TOTAL COST (?UL) : INR 39,500

## Project Overview

Our aim is to achieve the following with R.E.A.C.H.:
 1. Test Expermimental Hybrid Recovery Methods
 2. Set Asian Amateur Rocketry Record
 3. Breach Karmen Line

### Rocket Statistics

|Attribute       |Details                                                                       |Numbers              |Notes                      |
|:--------------:|:----------------------------------------------------------------------------:|:-------------------:|:-------------------------:|
|Dimensions      |8m Cylinder with 0.25 Nose Cone of 0.11m Radius                               |8.25 x 0.11          |Aluminium                  |
|Mass (Dry)      |-                                                                             |121Kg (?LL)          |-                          |
|Mass (Wet)      |-                                                                             |220Kg (?LL)          |-                          |
|Range           |100 Km (+ve Acceleration)                                                     |100Km/60Mi           |Karmen Line                |
|Communications  |Microwave Transmitter                                                         |120Km Range          |Tentatively Powered By ISRO|
|Logging & Data  |9 Degrees Sensor & 1080p Video & 3Hz Frame Capture                            |-                    |Refer to Electronics List  |
|Power           |10 9v Battery Array                                                           |90V DC               |-                          |
|Fuel (Solid)    |Dipropellant: (Alimunium + C<sub>31</sub>H<sub>64</sub>) + Ammonium Persulfate|60 MJ from 6.96Kg    |Energy Capacity            |
|Motor Dimensions|5.7m PVC Pipe 50mm with 0.105m Radius with 5-star bore                        |5.7 x (0.005 + 0.105)|Tentative & Detachable with Minimal Thrust Variance|
|Recovery        |Parachuteless Hybrid Recovery                                                 |Internal Sustained G<sub>max</sub> = 473G|Insanity|

## Trajectory Overview

Launch is expected at first light. Launch will be into Wind. Secondary Fins will induce a stabilizing spin. Communications will stream sensor data & 1080p Pictures (Color) @ 3fps.

At the the line, as acceleration is reported negative by sensors; the recovery fins, which have the radius of curvature of the rocket, will deploy & extend via compressed air. The connection point of the 3 fins will be 5cm above the ejection mechanism for the motor, just below the battery pack & compressed air tank. After successful telescoping, fins will lock into position and rocket will get a negative velocity.

Due to Center Of Mass & The Gyroscopic Effect, The rocket will exhibit formidable resistance to deflection from its axis of spin which will only improve as the rocket gains spin. However, the rocket will be allowed to drift in the XZ-Plane laterally.

When the rocket has drifted down to acceptable height (50m - 100m), the motor casing will be ejected & the compressed air will be routed to nozzles on the recovery fins. This will turn the whole contraption into a powered helicopter, generating lift, which would bring velocity to zero.

The rocket is then allowed to 'gently crash' into the ground; destroying the part of the fuselage that housed the motor and the fins to slow the rotation. The part of the fuselage above the junction (7+ m) of the recovery fins will be recoverable.

## Fuel Mixes

__Points to Consider:__

 1. Al oxidation to Al<sub>2</sub>O<sub>3</sub> is highly exothermic with 62 KJ/g of Al.
 2. OX decays exponentially above 80C. (TEMED Stabilizer Improves this)
 3. Burn Temperature Should not Exceed Melting Point of Casing.
 4. Thermal Conductivity of the Mix Should be Infinitesimal. (High C<sub>31</sub>H<sub>64</sub>% in Mix will help)
 5. Chamber Pressure should be constantly high. (High C<sub>31</sub>H<sub>64</sub>% in Mix will help)

__Current Mix Stands At 1 Kg Al with (4.54 + 1.32)Kg Ammonium Persulphate with 0.105Kg Paraffin Wax (C<sub>31</sub>H<sub>64)</sub>__

## Computational Framework

### Fuel-OX Ratio

<img src="eq_1.svg" width="95%" height="100" title="(NH4)2S2O8 ---1000+ K---> N2 + 2SO2 + 2H2 + 2O2">

All these products react and oxidize Al at elevated temperatures.

The net output of the reaction is approximately 58 KJ/g of Al.
 * <img src="eq_2.svg" width="50%" height="100" title="8Al + 6O2 -----> 4Al2O3">

Therefore 8Al atoms require 3OX molecules.
 * 1 mole of Al requires (N<sub>A</sub> / 8) * 3 moles of OX.
 * 27g of Al requires 515g of OX.
 * 1Kg of Al requires 19.07Kg of OX.

In order to breach Karmen Line, we require 4.2Kg of Al.
Therefore, 4.2Kg of Al requires 80.1 Kg of OX.

This is enough for the thermal requirement of the motor.

### OX-C<sub>31</sub>H<sub>64</sub> Ratio

<img src="eq_3.svg" width="80%" height="100" title="C31H64 + 47O2 ---500+ K---> 31CO2 + 32H2O">

 * The net output of this reaction is approximately 38 KJ/g of C<sub>31</sub>H<sub>64</sub>
 * This is required to maintain chamber pressure and improve efficiency at low external pressures.
 * Therefore 1C<sub>31</sub>H<sub>64</sub> requires 24OX molecules.
 * 1 mole of C<sub>31</sub>H<sub>64</sub> requires 24 moles of OX.
 * 436g of C<sub>31</sub>H<sub>64</sub> requires 5.5Kg of OX.

This is enough for Chamber Pressure creation.

__Total OX is 85.6 Kg in 171,200cm<sup>3</sup>__

__Total Al is 4.2 Kg in 1,556cm<sup>3</sup>__

__Total C<sub>31</sub>H<sub>64</sub> is 0.44Kg in 450cm<sup>3</sup>__

__Total Motor Mass ~91 Kg__

__Total Motor Volume 1.73206 x 10<sup>-1</sup> m<sup>3</sup>__

## Expected Data/Conditions

|Parameter        |Value                         |Notes    |
|:---------------:|:----------------------------:|:-------:|
|Range            |102+Km                        |-        |
|G<sub>max</sub>  |473G @ 0.11m from Axis @ 300Hz|-        |
|Burn Time        |~280s (?LL)                   |Tentative|
|Total Flight Time|900s (?LL)                    |-        |

##
