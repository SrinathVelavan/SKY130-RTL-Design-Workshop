# RTL Design  in Verilog using SKY130 Technology

<img src="images/Verilog-flyer.png">

## Project Scope

The project provides a detailed account of the 5-day workshop facilitated by VSD on RTL Design in Verilog using the SKY130 Technology. 

SKY130 is the hardware industry's first open-source process design kit (PDK) released by SkyWater Technology Foundry in collaboration with Google giving all hardware design experts and aficionados, a worldwide access to their IP functions and open source ASICs. More details [here.](https://github.com/google/skywater-pdk)

This particular workshop covers the various aspects of design in Verilog HDL both theoretically and practically with labs using open-source softwares through their VSD-IAT portal. Beginning with an introduction to digital design using Verilog HDL, the instructors cover digital design steps that include design, functional simulation, test bench based validation of the design functionality and logic Synthesis with optimization. Further, we learn about efficient verilog coding styles that result in a predictable logic in Silicon. 

## Getting Started

Users interested in practicing design using open-source tools need a Linux based OS and a host of open source EDA tools. More information regarding the installation and scripts can be found in the free UDemy tutorial [here.](https://www.udemy.com/course/vsd-a-complete-guide-to-install-open-source-eda-tools/?src=sac&kw=VSD+-+A+complete+guide+to)

Basic knowledge of Verilog HDL is required to follow the content without any difficulties

---
## Day 1 -  Introduction to Verilog RTL Design and Synthesis

The first day covers the basics of RTL Design, Testbench, Simulation and Synthesis. Open-Source softwares like iverilog (simulator) and YOSYS (Synthesis) are provided through remote access in the portal to practice labs.

RTL Design -  It consists of an actual verilog code / a set of verilog codes that have the functionality to meet the required design specifications of the circuit
TestBench - Testbench is a setup that one uses to apply a set of stimuli (test-case vector) to check the functional working of the design file

We do the above processes using a simulator software. The simulator is loaded with the design and its respective testbench file after which it looks for changes in the input signals and depending on the change, the output is evaluated. These changes in input and corresponding output values are dumped in a special format file called "value change dump" (.vcd) file. This file can be pictorially represented in waveforms using a waveform tool like gtkwave. 

We are given a default set of files and libraries shown below to work on using the practical lab instance

<img src="images/verilog_files.jpg">

