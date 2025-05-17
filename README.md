# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![WhatsApp Image 2025-05-17 at 14 06 45_f08ba163](https://github.com/user-attachments/assets/d892981e-1450-4a72-a7df-3e0517c35309)


#### Area report:
![WhatsApp Image 2025-05-17 at 14 06 45_ed075857](https://github.com/user-attachments/assets/fd2bd515-8940-4363-945e-bcdc64cd9a63)

#### Power Report:
![WhatsApp Image 2025-05-17 at 14 06 46_999a53c2](https://github.com/user-attachments/assets/5dc47f06-0557-4492-a3f3-5f6ffc093789)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
