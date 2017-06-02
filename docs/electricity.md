# Electrical components
The van itself is very simple on electronics: There is no motor control, everything is just mechanic switches or relais.
This page describes some found-out facts as well as some additions to the van.

## Generator
The van features a 12V generator that supplies approximately 25A when the engine is idle. It is rated up to 55A (at higher revolutions)

## Battery
The van came with a 45Ah lead acid battery, we added another 55Ah one in parallel. It is connected via 16mm² wires. Current measurements while charging, starting and discharging show approx. 2/3 of the current drawn from the new battery, meaning the old one might already have quite a high inner resistance.
This battery adds capacity to use more power for charging phones or operating devices even without the engine running.

A proper setup would include keeping the battery separated from the one starting the engine at lower charge levels. So far, the state of charge needs to be kept in mind when discharging for longer time periods.

## Radio
We found a Grundig WKC 5600 RDS radio that was easily modified to have an AUX input by using the CD input connector (see manual - connect C13 to ground to enable AUX, C18 Audio ground, C19 left, C20 right)
Because of problems of the radio not properly operating while the car was going, it is currently only connected to permanent power supply. Still, there might be something broken inside or at the power source.

The power source is the hazard flasher supply cable going to the steering wheel.
Standby current: 0.04A
Quiescent current: 0.75A

## Cigarette lighter socket
As the van did not have a cigarette lighter, we installed one parallel to the radio supply which is the permanent hazard flasher supply.

## Loading area sockets
We installed another cigarette lighter multi-socket (2x1A, 1x10A) in the back of the loading area. It is connected by 3x1.5mm² cabling (so 4.5mm²) to the second battery, fused by 20A.

## Loading area inverter
The loading area also features a 230V inverter that is able to put out up to 400W when the engine is running. Without the engine running, it manages to handle approx. 200-300W.

A power switch operates the standby control of the inverter.
Standby current: 0.02A
Quiescent current: 0.3A
Efficiency: approx. 85-90% (not including quiescent current)
