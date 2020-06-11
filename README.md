# DIY DRONE 

## INDEX

## INTRODUCTION
This project surges of my curiosity and interest in UAV's. Nowdays medium/larges drones and RC Trnasmitters are too much expensive; and the componentes used in are away one click, so the idea of making a DIY drone isn't far from reality. 

In this repository I will explain part by part of some drone flight theory and electronics theory, drone assembly, coding and construction of RC transmitter. The content will be split in three parts: Drone, Drone Comunication and Transmitter Comunication.  

## PARTS LIST
For the drone you need:
* Drone Frame
* 4xBrushless motors AA2212
* 4xproppellers (2x1045 and 2x1045R)
* 4xESC of 30 Amps
* Flight Controller CC3D
* Arduino PRO Mini or any type of Arduino
* Lithium Polymer Battery 11.1V 
* Nrf24l01 

For the RC you need:
* Nrf24l01
* LM7805
* LD333V
* Arduino PRO Mini
* Gyroscope
* 2xJoysticks 
* 2xSwitches
* Condersators
* Resistors
* 2xPushbuttons

## DRONE
There are many types of drones. 

I M A G E

I'll be making a quadcopter in HIBRYD-X configuration. Here are the standard directions of rotations on propellers of the HIBRYD-X, if you use an other flight controller, you can search or in the setup look for the directions of rotations on propellers and changed with out any problem. In this case the CC3D Flight controller managed the standar configuration.

I M A G E

The direction of rotation of the brushless motor depends in the 3 phases conncetion with the ESC. You can find more information about BLDC Motors in https://www.electronicshub.org/brushless-dc-motor-bldc-motor/. 

In my case the following configuration matches with my BLDC motors A2212. If you test them and doesn't follow the direction of rotation, you can inverse two cables, and test what configuration follow the direction you need acording to your quadcopetr configuration. 

I M A G E


### DRONE ASSEMBLY
### DRONE ELECTRONICS

## DRONE COMUNICATION
### DRONE FLIGHT CONTROLLER SOFTWARE

## TRANSMITTER COMUNICATION
### RCT

## REFERENCES
