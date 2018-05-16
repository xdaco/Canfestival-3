# README #

This is a free Free CanOpen stack, cloned from https://github.com/nucleron/CanFestival-3 which is actually further cloned from http://dev.automforge.net/CanFestival-3/ rev 8bfe0ac00cdb

### What is this repository for? ###

* This is one of the most famous and open source free CANOPen stack with almost all the implementation.
* Using this driver, We are writing a fake slave which will be used as bridge between any non compliant CAN node and ROS CANOpen master
* These codes assume that the host has a linux socketcan interface



### How do I get set up? ###

* Clone this repo using ssh
* Go to the project folder.
* Execute ```$ ./configure```
* Execute ```$ make``` to build
* Execute ```$ make clean ``` to remove build files
* To build SillySlave, go to examples/SillySlave
* Edit the  ```Makefile``` using any text editor. Go to line 42 and remove  ```“-lcanlib”``` and save the file.
* Execute ```$ make mrproper ```
* Execute ```$ make ```. This will build the binary for SillySlave on Unix/Linux platform

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
