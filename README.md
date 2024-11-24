# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2024-11-23 at 23 02 41_2b7eb8cb](https://github.com/user-attachments/assets/f8c08325-e8c3-4b40-b31d-b709c4c6ad07)

Area report:
![WhatsApp Image 2024-11-23 at 23 02 41_23380cf8](https://github.com/user-attachments/assets/7951113e-8e66-4b7f-98a2-fadcdac0734c)

Power Report:
![WhatsApp Image 2024-11-23 at 23 02 40_3c5620ab](https://github.com/user-attachments/assets/9963c0e4-ab7e-4388-b8f5-ac39db13c582)

Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
