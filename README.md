# Control-GCSAgrisenaRP
On this page, we will explain the components and control system scheme for the UAV fixed wing vehicle for the KRTI racing plane competition (Agrisena Racing Plane) with V-Tail configuration


# Varshata V1.0 #



# Tools (Hardware) and Software #
1. Pixhawk 2.4.8 
2. Motor Brushless T-Motor 3520 850 KV
3. ESC T-Motor 75 A
4. Servo EMAX ES08MII Metal gear
5. Telemetry Holybro 433 Mhz 500 mW
6. GPS SE Radiolink series
7. Frsky X8 Receiver
8. Jumper T18 TX transmitter
9. Buzzer and Safety Switch
10. Mission planner (software GCS)
11. 6S Battery CNH Black 2000 mAh (x2)
12. Moxon antenna/ Antenna TUNED Ground Plane RPSMA (For telemetry Base)
13. ELRS Receiver (Recommend)

# Schematic Hardware #
Pixhawk 2.4.8 is a flight control that has easy compatibility with various actuators and sensor systems for making UAV vehicles

1. Motor brushless with ESC >>>> connect to channel 3 main-output in pixhawk 
2. 2 servo (for aileron) >>>> connect to channel 1 & 6 main-ouput in pixhawk
3. 2 Servo (for tail) >>>> connect to channel 2 & 4 main-output in pixhawk
4. Receiver Frysky X8 (SBUS mode) >>>> connect to RC-IN channel in pxhawk
5. Telemetry (remote) >>>> connect to TELEM1/TELEM2 socket in pixhawk (JST socket)
6. GPS SE Radiolink (Have 2 cable, for GPS (4 hole) and I2C (2 hole)) >>>> connect to GPS Socket and I2C Socket in pixhawk 
7. Buzzer and safety switch >>>> connect to buzzer socket and safety switch socket









