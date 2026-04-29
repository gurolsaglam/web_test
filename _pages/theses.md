---
layout: page
title: Theses
permalink: /theses/
---

<style>
  .entry hr {
    background-color: #eee;
    border-color: #eee;
    color: #eee;
    border: 0;
    height: 1px;
  }
</style>


**FPGA Implementation of OFDM based VLC &mdash; M. Sc. Thesis** <span class="time_period">Sept 2022</span>

**[nEMESysLab](https://ugurdag.com/nemesyslab.html), [Özyeğin University](https://www.ozyegin.edu.tr) &mdash; Turkey**

In this thesis, DC Biased Optical OFDM (DCO-OFDM) for a VLC System was implemented on an FPGA. OFDM was originally devised as an RF methodology to carry multiple data within different frequencies in a signal. DCO-OFDM, however, is a specific category of OFDM that creates a signal transmittable via light sources (e.g. LEDs). Due to the high complexity of calculations in DCO-OFDM, it was implemented on an FPGA to meet the ever-increasing demand for higher bandwidth.

- Implemented DC Biased Optical OFDM (DCO-OFDM) for a Visible Light Communication System on FPGA in Verilog
- Leveraged Intel's Altera's Arria 10 SoC Development Kits and Analog Devices' AD-FMCDAQ2-EBZ Evaluation Boards, addressing required design area and ADC/DAC conversion precision along with sampling rate
- Addressed the high complexity of DCO-OFDM calculations by taking advantage of FPGA design
- Achieved 3.22x and 2.92x faster modulation with respect to state-of-the-art
- Created testbenches for each module for verification, ensuring functionality
- Used Matlab to simulate OFDM, and generate input and expected output for verification
- **Publication:** V.E.Levent, **G.Saglam**, H.F.Ugurdag, N.F.R.Annafianto, F.Aydin, S.W.Tesfay, B.Aly, M.Elamassie, B.Kebapci, M.Uysal, FPGA Based DCO-OFDM PHY Transceiver for VLC Systems, 11th International Conference on Electrical and Electronics Engineering (ELECO), IEEE, Nov, 2019

---

**Synthesis of Customized Processors for Specific Software Tasks &mdash; B. Sc. Thesis** <span class="time_period">June 2019</span>

**[nEMESysLab](https://ugurdag.com/nemesyslab.html), [Özyeğin University](https://www.ozyegin.edu.tr) &mdash; Turkey**

In this thesis project, the problem was defined as 'creating the best fitting customized Very Simple CPU for a given software program'. The project delivered the Instruction Super Set Simulator (ISSS), written in Python using Object Oriented Programming. ISSS is able to take a compiled assembly code from the user and create the optimized memory (RAM/ROM) implementations and Very Simple CPU soft core with only the required ALU implemented in Verilog HDL. It is also able to simulate it on the command line for debugging purposes. The project also delivered a Tcl script, in which all the designs are added to a Xilinx project and synthesized. You can find more information on VSCPU here: [http://cpu.tc](http://cpu.tc)

- Developed a comprehensive tool in Python/Perl/Tcl called Instruction Super Set Simulator (ISSS)
- Translated compiled assembly code into objects in fully Object Oriented Programming fashion
- Added support for VSCPU v1 and VSCPU v2 which supports floating point operations, along with instruction extensions for Lightweight Cryptographic Systems (FELICS)
- Implemented debugging capabilities with command-line simulation
- Integrated tool into ISSS for customization of the Very Simple CPU, creating a customized soft core in Verilog HDL
- Integrated tools into ISSS for customization and optimization of memory, creating tailored memory Implementations
- Created a Tcl script for synthesis, place-and-route and bitstream generation as a Xilinx project
- **Publication:** A.Varici, **G.Saglam**, S.Ipek, A.Yildiz, S.Goren, A.Aysu, D.Iskender, T.B.Aktemur, H.F.Ugurdag, Fast and Efficient Implementation of Lightweight Crypto Algorithm PRESENT on FPGA through Processor Instruction Set Extension, IEEE East-West Design & Test Symposium (EWDTS), IEEE, Sep 2019
