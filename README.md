# CSUSB-SUMO-Simulation
Custom SUMO Simulation CSUSB

![CSUSB_SUMO_SIM](https://user-images.githubusercontent.com/45495586/135019144-8b1a8d77-0785-431d-8138-f1f188287fc4.gif)

## Issues with randomTrips.py file
If the randomTrips.py file does not create an output file: https://stackoverflow.com/questions/67717897/sumo-random-trips-xml-file-not-generating
To make things easier: you can copy the randomTrips.py file from the SUMO/tools directory to directory containing the .net.xml files. Otherwise, you will need to run cmd as admin in the SUMO/tools folder.

## How to run the simulation
1. Open SUMO
2. Click file -> Open Simulation -> select the csusb.sumo.cfg file
3. Slow the simulation down by changing the delay value to 80 or desired value.
4. There is a dropdown box that will allow you to change the backround color to green or other options
5. press the green play button to start the simulation

## Note
You need to slow down the simulation as desribed above or you won't be able to see much.
