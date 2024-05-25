
#  Android-RasPi-WifiP2P-Communication

PiBLE/Pi contains the scripts you need to use this tool.

This is repo contains a template/example of setting up a Wifi Direct connection between a Raspberry Pi Zero W and an android phone. Contains config scripts as well as (WIP) code for setting up a connection, setting up a TCP socket, and exchanging data on both the Android and the Pi

Links:
https://raspberrypi.stackexchange.com/questions/117150/issue-connecting-raspberry-pi-to-android-via-wifi-p2p

https://raspberrypi.stackexchange.com/questions/117718/how-to-connect-an-android-phone-and-a-raspberry-pi-through-wifi-direct-programma
  

##  Documentation

###  Basic Usage

    python wifi_direct_connector.py

Runs the script waiting for serial commands to control device actions.

###  Direct Connection with Device Name

    python wifi_direct_connector.py MySensorDevice

Immediately attempts to connect to the device named "MySensorDevice" using Wi-Fi Direct.

  

###  Custom Serial Port and Baud Rate

    python wifi_direct_connector.py /dev/ttyUSB0 115200

the specified /dev/ttyUSB0 port and 115200 baud rate for serial communication.
