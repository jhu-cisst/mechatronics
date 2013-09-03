---
layout: default
title: Mechatronics
---

# Open Source Mechatronics
This site is dedicated to the development of open source mechatronics. Specifically, it contains design files and documentation for a motor controller with an IEEE-1394a (Firewire) interface. The controller consists of two boards: FPGA1394 and QLA. The FPGA1394 board contains a Xilinx FPGA to minimize the latency between the Firewire bus and the controller I/O. The Quad Linear Amplifier (QLA) board contains four linear amplifiers for controlling four DC brush motors. These controllers can be used to drive the da Vinci Research Kit, which consists of the mechanical components of the first-generation da Vinci (known as the da Vinci Classic).

Please check the SVN repository, either by using the Browse Source tab above or by doing an SVN checkout from  [https://svn.lcsr.jhu.edu/mechatronics/trunk](https://svn.lcsr.jhu.edu/mechatronics/trunk).

See also  [Robotics Infrastructure - Mechatronics](https://www.lcsr.jhu.edu/Infrastructure/Mechatronic).


## Documentation

### Software
 * [Development Eveironment (Linux)](https://trac.lcsr.jhu.edu/mechatronics/wiki/DevelopmentEnvironment)
 * [Interface Specification (IEEE-1394 packet formats)](https://trac.lcsr.jhu.edu/mechatronics/wiki/InterfaceSpec)
 * [Low-level Software API](https://github.com/jhu-cisst/mechatronics-software/wiki/Low-Level-Software-API)
 * [Low-level Example Programs](https://github.com/jhu-cisst/mechatronic)
 * [da Vinci Research Kit](https://trac.lcsr.jhu.edu/cisst/wiki/sawIntuitiveResearchKitTutorial)

### Hardware


