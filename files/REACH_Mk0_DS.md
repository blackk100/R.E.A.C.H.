<!-- Uses GitHub Flavoured Markdown-->

# R.E.A.C.H. Mk0 Data Sheet

## Key

 1. __(?UL) - Indicates that value falls in the higher range of possible values__
 2. __(?LL) - Indicates that value falls in the lower range of possible values__

## Project Overview

Our aim is to achieve the following with R.E.A.C.H.:
 1. Develop & test a cost-effective solution for experimental testing of new concepts;
 2. Mk0 aims to test a novel recovery method;
 3. Set Amateur Asian Record for Altitude (Apoapsis) and Eurasian Record for Range of an Amateur Rocket;
 4. Ultimately breach the Karman Line.

__TGT: Break Aerospace Limit__

__Total Budget: 70,000 INR__

We expect some assistance from research organizations for infrastructural support.

[Infrastructure Outsourcing List](External_Infrastructure.md)

### Rocket Statistics

|Attribute       |Details                                                   |Numbers                                 |Notes                                                 |
|:--------------:|:--------------------------------------------------------:|:--------------------------------------:|:----------------------------------------------------:|
|Dimensions      |2m Cylinder with 0.1 Nose Cone of 0.05m Radius            |2.1 x 0.05                              |Aluminium 6061-T6                                     |
|Mass (Wet)      |-                                                         |4Kg                                     |-                                                     |
|Range           |100 Km (+ve Acceleration)                                 |100Km/60Mi                              |Karman Line                                           |
|Communications  |Microwave/RF Transceiver                                  |120Km Range                             |Undecided                                             |
|Logging & Data  |9 Degrees Sensor & 1080p Video & 3Hz Frame Capture        |-                                       |Refer to Electronics List                             |
|Power           |Internal, Reinforced battery pack                         |-                                       |-                                                     |
|Fuel (Solid)    |Bipropellant: (Aluminium + HTPB) + Ammonium Perchlorate   |9.92 MJ/Kg                              |Energy Capacity                                       |
|Motor Dimensions|Titanium Alloy Grade 6 Pipe 0.04m Radius with 5-star bore |-                                       |Designed to be detachable with minimal Thrust variance|
|Recovery        |Parachute-less Hybrid Recovery                            |Internal Sustained G<sub>max</sub> = 45G|Insanity                                              |

## Trajectory Overview

Launch is expected at first light. Launch will be into Wind. Secondary Fins will induce a stabilizing spin.

Communications will stream sensor data & 1080p Pictures (Colour) @ 3fps.

At the line, as acceleration is reported negative by sensors; the recovery fins, which have the radius of curvature of the rocket, will deploy & extend via compressed air.

The connection point of the 3 fins will be 5cm above the ejection mechanism for the motor, just below the battery pack & compressed air tank. After successful telescoping, fins will lock into position and rocket will get a negative velocity.

Due to Centre of Mass & the Gyroscopic Effect, The rocket will exhibit formidable resistance to deflection from its axis of spin which will only improve as the rocket gains spin. However, the rocket will be allowed to drift in the XZ-Plane laterally.

When the rocket has drifted down to acceptable height (50m - 100m), the motor casing will be ejected & the compressed air will be routed to nozzles on the recovery fins. This will turn the whole contraption into a powered helicopter, generating lift, which would bring velocity to zero.

The rocket is then allowed to 'gently crash' into the ground; destroying the part of the fuselage that housed the motor and the fins to slow the rotation. The part of the fuselage above the junction (1.75+ m) of the recovery fins will be recoverable.

## Build Materials

 1. ### Structural

	|S No |Part                                       |Projected Cost              |Quantity|Notes                                                   |
	|:---:|:-----------------------------------------:|:--------------------------:|:------:|:-------------------------------------------------------|
	|1    |Aluminium 6061-T6 10mm                     |INR 5000/m<sup>2</sup> (?UL)|1.5     |Fuselage is 0.05 (Radius) x 2 (Height) + 0.1 (Nose Cone)|
	|2    |Stainless Steel Cylinder 0.06m x 0.1m      |INR 2000                    |1       |-                                                       |
	|3    |Welding Tools                              |INR 2000                    |DNM     |-                                                       |
	|4    |Compressed Air Tank 15L @ 2 atm            |INR 3400 (?UL)              |1       |Dimensions are Tentative                                |
	|5    |Lever/Latch Locks                          |INR 250                     |4       |-                                                       |
	|6    |Aluminium/Copper/Plastic/Rubber Tubing 20mm|INR 500/m (?UL)             |2       |-                                                       |
	|7    |Gas Valves 20mm                            |INR 100                     |2       |Rated for 4 Atm                                         |
	|8    |Servos                                     |INR 300 (?UL)               |4       |For Valve Operation                                     |
	|9    |Shock Absorbent Foam                       |INR 400/m<sup>2</sup> (?UL) |1.5     |Non-Flammable                                           |
	|10   |Telescopic Recovery Fins                   |Custom                      |3       |1.75 + 1.5 + 1.25                                       |
	|11   |Gyroscopes                                 |INR 400                     |2       |-                                                       |
	|12   |Titanium Alloy Grade 6 Pipe 0.045m x 1.2m  |INR 15000                   |1       |                                                        |

	_Assorted Adhesives & Tools & Mounts Not Included_

	**Total (?UL): 35,300 INR**

 2. ### Solid Rocket Motor

	|S No |Chemical                         |Projected Cost/KG|Projected Quantity (?UL)|Notes        |
	|:---:|:-------------------------------:|:---------------:|:----------------------:|:------------|
	|1    |Laboratory Grade Aluminium Powder|INR 300          |1                       |Main Fuel    |
	|2    |Polybutadiene Pellets            |INR 200          |1                       |Binding Agent|
	|3    |Ammonium Perchlorate             |INR 200          |3                       |OX           |

	_Material for Test Fires Not Included_

	**Total (?UL): 3,000 INR**

 3. ### Electronics
	__See [Full Part List](Electronics_List.md)__

	**Total (?UL): INR 20,000**

### TOTAL COST (?UL): 60,300 INR

## Fuel Mixes

__Points to Consider:__

 1. Al oxidation to Al<sub>2</sub>O<sub>3</sub> is highly exothermic with 62 KJ/g of Al.
 2. Burn Temperature should not exceed Melting Point of casing.
 3. Thermal Conductivity of the Mix should be infinitesimal. (BDR will help)
 4. Chamber Pressure should be constantly high. (BDR will help)
 5. Mixtures denoted in the following convention; Binder/OX/Fuel Mass %

 |                        |Stoichiometric     |JAXA/ISRO               |Wikipedic          |
 |:----------------------:|:-----------------:|:----------------------:|:-----------------:|
 |Mass Composition        |12/58/30           |12/68/20                |16/68/16           |
 |Quantized Fuel Unit     |3.4g               |5g                      |6.25g              |
 |Total Mass              |2660g              |2660g                   |2660g              |
 |Fuel Units              |782                |532                     |425                |
 |Range (1% EF)           |12Km               |8Km                     |6Km                |
 |Target System EF (100Km)|9%                 |13%                     |16%                |
 |Mix Volume              |1377cm<sup>3</sup> |1426cm<sup>3</sup>      |1494cm<sup>3</sup> |
 |Tube Length @ 3cm Radius|98cm               |102cm                   |106cm              |
 |Gas Evolution Rate      |0.44 mol/s         |0.65 mol/s              |0.84 mol/s         |
 |Burn Temperature        |873K               |773K                    |673K               |
 |Internal Pressure       |NA                 |1.45 x 10<sup>8</sup> Pa|NA                 |

## Computational Framework

<img src="https://latex.codecogs.com/svg.latex?\large&space;2NH_{4}ClO_{4}&space;\overset{500&plus;K}{\rightarrow}&space;N_{2}&space;&plus;&space;3H_{2}&space;&plus;&space;2HCl&space;&plus;&space;4O_{2}"
title="\large 2NH_{4}ClO_{4} \overset{500+K}{\rightarrow} N_{2} + 3H_{2} + 2HCl + 4O_{2}"/>

#### Stoichiometric Mixture Calculation

 16 mol Al requires 6 mol OX

 => 432g Al requires 705g OX

 => 1g Al requires 1.7g OX

 ***The Mass Percentage of Al is 37%***

 ***The Mass Percentage of OX is 63%***

##
