# NeuroSky MindWave Mobile interface builder
### This is a work in progress and by no means a usable product (yet). Feel free to help its development.
Debug and use the data from NeuroSky Mindwave Mobile using the Start Wars Force Trainer II with Bluetooth or similar.

The aim of this project is to provide an easy way to develop a "usable" interface for users with disabilities and enable them to perform certain actions. My main goal is to allow them to speak using brain activity and a set of pre-defined phrases but this should work with other goals in mind.

## Start Wars Force Trainer II
This NeuroSky device is the cheapest you can get your hands on, the catch is that is meant for kids to is quite small for normal use but it comes with bluetooth and no modification to the hardware is needed to use the data.

## Connect your NeuroSky device
Using bluetooth, pair your device with your computer, the comunnication is done via Bluetooth Serial.

Mac users have to open a serialport connection to ```/dev/cu.ForceTrainerII-SerialPo```.

The details for the communication protocol can be found here: http://developer.neurosky.com/docs/doku.php?id=thinkgear_communications_protocol

#Dependencies
Mindwave plugin code taken from @elsehow https://github.com/elsehow/mindwave and modified to suit this project.
