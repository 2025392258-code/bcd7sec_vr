<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project converts a 4 bit BCD input into a 7segment display output The input is processed by a decoder that activates the corresponding segments to display decimal numbers from 0 to 9 The design is implemented using digital logic on an FPGA board

## How to test

To test the project program the FPGA board with the generated configuration file. Use the input switches to select different 4-bit BCD combinations The 7-segment display should show the corresponding decimal number for valid BCD inputs 0000 to 1001

## External hardware

 FPGA development board Basys 2
 On-board switches for BCD input
 On-board 7 segment display for output
 USB programming cable
