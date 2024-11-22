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
![WhatsApp Image 2024-11-22 at 12 14 58_a3b3e0f5](https://github.com/user-attachments/assets/9d40256f-2f62-404b-9db0-77fac07449dc)

#### Area report:
![WhatsApp Image 2024-11-22 at 12 15 35_32e5079c](https://github.com/user-attachments/assets/bfbfb853-dd9c-46da-9f1b-8e0e7f78e02d)

#### Power Report:
![WhatsApp Image 2024-11-22 at 12 15 36_c40301d0](https://github.com/user-attachments/assets/f237b1c8-1311-410d-b9a8-de144141d529)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
