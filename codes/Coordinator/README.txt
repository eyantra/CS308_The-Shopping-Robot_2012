This file explains the code of the coordinator.

Create a project in visual C++( refer to the screencast for this) and copy these files in the project folder.

There are 6 header files and one main file.
The main file(main.cpp) contains the code for all the actions the coordinator should perform on receiving a signal from any bot.
The important functions are delivery and gripper. The names explain that they are the routines for the delivery and gripper bots respectively.

The header files are:
1) init.h : contains all the initializations for the COM Port for xbee as well as  various variable initializations.
2) functions.h : contains some useful functions used at various points.
3) point.h : contains the defination of the class point.
4) structs.h : contains the defination of various classes created.
5) rfid.h : contains the defination of the class for the physical objects
6) xbee.h : contains functions to send and receive data using zigbee.