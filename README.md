# ELEN90032 Sensor Systems Project
Report and source code for the projects for ELEN90032 Sensor Systems subject.
## Author
## Harfiyanto Dharma Santoso (harfiyanto@gmail.com)

## Project 1: Pedometer
Pedometer implementation using a multi-axis accelerometer (ADXL335) and Arduino MEGA Development board.

## Project 2: Altimeter
Altimeter implementation using both an accelerometer (ADXL335) and a atmospheric pressure sensor (BMP280).

## Project 3: Indoor Localization System
Indoor Localization System implementation using accelerometer (ADXL335), pressure sensor (BMP280), and RSSI sensor (SparkFun ESP32 Thing).
The aim is to approximate the location of a traveling subject in a 10 by 10m room using acceleration and pressure readings and compare the accuracy to RSSI method. The readings would be processed together on the Arduino board and transmitted via an Internetof Things (IoT) framework to display the target’s location on a webserver. A Kalman filter is implemented to filter out the noise.
