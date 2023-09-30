# Automatic-Test-Bench-Generator-using-python

In this project the students will design Automatic Test Bench generator. The input will be Verilog DUT, the results will be Testbench that initialize variables using initial block, generate clock, instantiate the input DUT into the Testbench, and use always/initial with appropriate time delays 
to create test stimulus. 

You can use mix of directed tests and $random Verilog function, you should also add display and monitor in you generated. 
Verilog TB, to allow running this automatically created TB through simulation and validate the results.

__Requirements__

• Select a name for your Automatic TB generator

• You should be able to parse Verilog code of the DUT to extract Input Ports, Variables, If Condition Expression, Case Conditions, ..

    o Verilog Module
  
    o Input, Output Ports
  
    o Registers, Wires
  
    o Continuous Assignments
  
    o Always Block (Combinational, Clock Based)
  
    o If , Case
  
    o Non-Blocking Assignment
  
    o Logical Operator

• Your generator should be constructed from
  
    o Verilog Parser, that also extract control flow of your design (if/else, branches, cases,)

    o Stimulus Generator (Sequencer, Driver)
  
    o TB Writer: TB Module, Initial Block for Initialization, Clock Generation, Instantiation, Tests Generator, Monitor.
