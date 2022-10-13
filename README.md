--------------------------------------------------------------------------------------------------------
Guide -> On-Line System Identification of Electric Power System Linear Models
--------------------------------------------------------------------------------------------------------
National Autonomous University of Mexico (UNAM)

Author:   José Alberto Moreno Corbea                

This file contains the instructions to run the Electric Power System Simulator (EPS_SIMULATOR)
and the tool for the identification of its linear model. DIgSILENT and MATLAB environments are
used in this implementation. The entire application was developed using the DIgSILENT Programming
Language (DPL) and MATLAB scripts.

--------------------------------------------------------------------------------------------------------
Instructions:
--------------------------------------------------------------------------------------------------------
1- Unzip the folder "EPS_SIMULATOR" contained within the file "EPS_SIMULATOR.rar" in the
   directory (C:\\EPS_SIMULATOR).

2- Open the principal MATLAB script "MAIN.m" but don't run it yet.

3- Import the DIgSILENT file "EPS_SIMULATOR.pfd" and activate the project.

4- Run the MATLAB script "MAIN.m" and then execute the DIgSILENT script "FAULT" inside the
   activated project.

5- A GUI will appear showing the real-time simulation and the results of the identification
   process of the Electric Power System Linear Model.

6- The Matrices A, B, C and D in continuous time will be saved in the directory (C:\\EPS_SIMULATOR\...)
   as "*.mat" files when the identification process is done. 



--------------------------------------------------------------------------------------------------------
This application was developed on a PC with the following properties
--------------------------------------------------------------------------------------------------------
Processor: Intel(R) Xeon(R) CPU E5-1620 v4, 3.5 GHz 

RAM      : 32 GB

OS       : Window 10, 64 bits
