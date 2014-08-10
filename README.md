HDL-xLibCores
=============

HDL x-library of IP Cores

External tools and libraries
----------------------------

* CMake 2.8
* Verilator 3.862
* SystemC 2.3.1
* Google C++ Testing Framework gtest-1.7.0
* Doxverilog 1.8 (patched Doxygen 1.8.5 for verilog)

Build
-----

To build all modules in Linux:

    mkdir build
    cd build
    cmake ..
    make

To clean workspace:

    make clean

Documentation
-------------

To generate documentation for verilog modules:

    doxverilog Doxverilog.cfg
