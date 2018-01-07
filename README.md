# pwmdemo

This program represents a demonstration of the PWM hardware that may exist in a petalinux or yocto project on a Digilent FPGA/ARM board.

This demonstration can be used to list information about any PWM devices that are found amongst the UIO devices present on a system. The program currently seeks to find a PWM device with the name matching "PWM" and automatically seeks to use this hardware for the demo.

The PWM portion of the demo will simply cycle through colors on a basic RGB LED. 

This demo is automatically built into the Petalinux projects for the [Arty-Z7-20](https://github.com/Digilent/Petalinux-Arty-Z7-20), and the [Zybo-Z7-20](https://github.com/Digilent/Petalinux-Zybo-Z7-20).
