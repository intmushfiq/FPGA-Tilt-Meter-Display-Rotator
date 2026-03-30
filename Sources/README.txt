Source : EEE304_Project.v  // It is the main verilog code file
Constraints : EEE304_Project.xdc  // It holds the I/P ports
IP Catalog : cordic_0.xci  // CORDIC algorithm for arctan calculation. Have to add this file in the vivado project separately

Project Setup Process - 
1. Open a new Vivado project
2. Add EEE304_Project.v as the source file
3. Add EEE304_Project.xdc as the constraint file
4. Create project
5. Add CORDIC IP core : Setting -> IP Catalog -> DSP and Math -> CORDIC -> Function Selection -> Arc Tan -> OK
