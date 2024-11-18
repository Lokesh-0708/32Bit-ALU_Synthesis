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
![WhatsApp Image 2024-11-18 at 18 10 40_d0ea12ec](https://github.com/user-attachments/assets/58bca46c-1a08-42f9-af9a-696c03501226)

#### Area report:
![WhatsApp Image 2024-11-18 at 17 52 19_73c92182](https://github.com/user-attachments/assets/51770d14-62e1-45b7-a62e-b7ef30c551d6)

#### Power Report:
![WhatsApp Image 2024-11-18 at 17 52 08_fcb28f35](https://github.com/user-attachments/assets/31a27420-d4be-4985-917c-24a11c85cd96)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
