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
![WhatsApp Image 2024-11-22 at 12 14 58_d81ad187](https://github.com/user-attachments/assets/081f13dd-a063-4458-bdd7-635593d9a2e7)

#### Area report:
![WhatsApp Image 2024-11-22 at 12 15 35_bf8f7fc4](https://github.com/user-attachments/assets/0aef4209-cf3a-42bb-a8c7-6b0044d4f865)

#### Power Report:
![WhatsApp Image 2024-11-22 at 12 15 36_5e5906ec](https://github.com/user-attachments/assets/c1f94e8c-c124-4309-be0c-c46a63235ffb)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
