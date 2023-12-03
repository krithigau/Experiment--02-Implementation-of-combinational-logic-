# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Procedure
Create a New Project

Open Quartus and create a new project by selecting "File" > "New Project Wizard."
Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).
Create a New Design File:

Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.
Write the Combinational Logic Code:

Open the newly created Verilog or VHDL file and write the code for your combinational logic.
Compile the Project:

To compile the project, click on "Processing" > "Start Compilation" in the menu.
Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.
Analyze and Fix Errors:*

If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
Review and fix any issues in your code if necessary.
View the RTL diagram.
6.*Verification:

Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
Give the Input Combinations according to the Truth Table amd then simulate the Output Waveform
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: U KRITHIGA
RegisterNumber: 23006499 
*/
![Code exp2](https://github.com/krithigau/Experiment--02-Implementation-of-combinational-logic-/assets/150319401/e01ace57-41b5-47c2-88ea-24ff25109d95)

### Truth Table
![TT 1st fig](https://github.com/krithigau/Experiment--02-Implementation-of-combinational-logic-/assets/150319401/075b02f5-af2c-4d27-8d74-2cc19d25c83c)

![TT for EXP 2](https://github.com/krithigau/Experiment--02-Implementation-of-combinational-logic-/assets/150319401/e435660b-bd07-45ec-abd5-58dc0f4e3093)

## RTL realization

![RTL FOR EXP2](https://github.com/krithigau/Experiment--02-Implementation-of-combinational-logic-/assets/150319401/ed3eda51-1f06-45a2-a2bd-a3ad30f586dd)

## Output:
![E2 Timing](https://github.com/krithigau/Experiment--02-Implementation-of-combinational-logic-/assets/150319401/99e9363e-df50-476b-9a32-d25403cfdc0f)

## Timing Diagram
![Screenshot 2023-12-03 201025](https://github.com/krithigau/Experiment--02-Implementation-of-combinational-logic-/assets/150319401/9ca75a1d-e56d-4b44-a2a0-613eecf63dc1)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
