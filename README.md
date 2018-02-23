IIoT-SPYN

IIoT-EDDP: Industrial IoT Electric Drive Demonstration Platform is an open-source project that provides all necessary software and hardware components for development and evaluation of motor control applications. 

PYNQ: Python on Zynq is an open-source project from Xilinx that makes it easy to design embedded systems with Zynq All Programmable Systems on Chips (APSoCs). Using the Python language and libraries, designers can exploit the benefits of programmable logic and microprocessors in Zynq to build more capable and exciting embedded systems. 

IIoT-SPYN: Industrial IoT SPYN is an open source project that leverages  IIoT-EDDP and PYNQ. Using IIoT-SPYN users can control, monitor, capture data, visualize and analyze Industrial grade motors. 

IIoT-SPYN is intended to work with the EDDP kit. Here is the link to purchase the kit: EDDP Kit



Quick Start

On the latest PYNQ image, use the following command in a terminal to install SPYN-Starter

    $ sudo pip3.6 install --upgrade git+https://github.com/Xilinx/SPYN-starter.git
    $ sudo reboot now

After the setup, new Jupyter notebooks will be added under the spyn folder, ready to try out, no additional steps are needed.



Folder Structure

- images : contains images that are used in the jupyter notebooks
- notebooks : contains jupyter notebooks that interact with the motor
- spyn: package that contains lib and overlays folders
  - spyn/lib: contains library files of the IIoT-SPYN project. 
  - spyn/overlays: contains the bitstream and the tcl file. 



Supported Boards

- Arty-Z7-7020
- PYNQ-Z1
- Arty-Z7-7010 will supported from March 2nd 2018



Licenses

PYNQ License : BSD 3-Clause License

IIoT-EDDP License : BSD 3-Clause License

IIoT-SPYN License: BSD 3-Clause License


