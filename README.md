# SmartShell
This project contains the SmartShell hardware design and source code of wireless configuration and SmartShell APP.

The source code of wireless configuration should be compilated by TI Code Composer Studio 12.1.0. The source code of the SmartShell APP should be compilated by android studio 2021.3.1.17.

# Overview
SmartShell use a small-sized and low-cost reflective surface attached to the mobile device to program the micro-environment of radio propagation near the device. The system consists of five main parts:(1)The array optimization algorithm running in the SmartShell APP installed on the mobile device.(2)The Wi-Fi RSSI collection thread running in the mobile device that calls system function to measure real-time RSSI values and put them to the optimization algorithm as the feedback. (3)The antenna array which accepts the MCU commands to control each element's impedance.(4)The BLE configuration mechanism that conveys the array control commands genreated by the mobile device to the MCU.(5)An energy harvesting circuit that provides energy for the SmartShell hardware independent of the mobile device. Here parts (1) and (2) are integrated into a single SmartShell APP.
