# bram
### Simple Verilog RAM/ROM module to use Block RAM on FPGA

bram has active low Chip Select, Read, and Write pins, and variable address width and data width. Tested on an iCE40HX8K, but it should work as-is on any of the iCE40 FPGAs, using block ram provided the chip contains enough block ram to accomodate the selected address and data widths. 
