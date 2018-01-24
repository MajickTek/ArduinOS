# ArduinOS
Serial OS For any Arduino

## About

This "OS" supports networking with specific hardware.

It also contains color support, special character support, and more.

It cannot run in Arduino's defualt Serial prompt, so you will need to use PuTTY.

Putty Start Command: -serial COM15 -sercfg 115200,8,n,1,N
Where COM15 is your board's COM port.

PuTTY is required for displaying the proper serial information.
get it from here: https://www.putty.org

The OS is compatible with any and all arduinos that come in contact with it.

You don't even need to install network support/have the rquired hardware installed.

## Build

Hardware required:
* Arduino board (Personally tested on Uno; works with all boards)

* The board needs to be connected to a computer at all times for the correct serial connection (BlueTooth could be an option; not tested)

* Breadboard (only if installing additional components)

Software required:
* Arduino IDE for programming the board
