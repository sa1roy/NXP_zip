Overview
========
The lpuart_edma Example project is to demonstrate usage of the KSDK lpuart driver.
In the example, you can send characters to the console back and they will be printed out onto console
 in a group of 8 characters.

Toolchain supported
===================
- IAR embedded Workbench  8.50.1
- GCC ARM Embedded  8.3.1

Hardware requirements
=====================
- Micro USB cable
- i.MX8QM MEK Board
- MCIMX8-8X-BB
- J-Link Debug Probe
- 12V power supply
- Personal Computer
- USB to RS232 Convertor

Board settings
==============
Connect USB to RS232 Convertor to J37 (On base board) if there's no RS232 port on your host PC.

Prepare the Demo
================
1.  Connect 12V power supply and J-Link Debug Probe to the board.
2.  Connect the serial cable between the host PC and the J37 on base board.
3.  Open a serial terminal with the following settings:
    - 115200 baud rate
    - 8 data bits
    - No parity
    - One stop bit
    - No flow control
4.  Download the program to the target board (Please refer "Getting Started with MCUXpresso SDK for i.MX 8QuadMax.pdf" for how to run different targets).
5.  Launch the debugger in your IDE to begin running the example.

Running the demo
================
When the example runs successfully, the following message is displayed in the terminal:

~~~~~~~~~~~~~~~~~~~~~
LPUART EDMA example
Send back received data
Echo every 8 characters
~~~~~~~~~~~~~~~~~~~~~
Customization options
=====================

