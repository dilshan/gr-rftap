# gr-rftap

## RFtap Module for GNU Radio

This module implements the [RFtap](https://rftap.github.io/) Encapsulation block, used to encapsulate Radio Frequency (RF) metadata about packets for Wireshark. Interoperability was tested with gr-rds, gr-ieee802-11, gr-ieee802-15-4.

You can connect the RFtap Encapsulation block in your flowgraphs to any block that has a PDU Message output port.

See: https://rftap.github.io/

## Installation

### GNU Radio

There are several ways to install GNU Radio. You can use

#### Prebuilt Binaries

The recommended way to install GNU Radio on most platforms is using available binary package distributions. 

The following command is for Debian, Ubuntu, and derivatives. Consult your distribution information to obtain the version of GNU Radio which is included.

    sudo apt install gnuradio

For other operating systems and versions, see [Quick Start](https://wiki.gnuradio.org/index.php/InstallingGR#Quick_Start)

#### From Source

Complete instructions for building GNU Radio from source code are detailed in 
[Installing From Source](https://wiki.gnuradio.org/index.php?title=LinuxInstall#From_Source). 

### Manual Installation of gr-rftap

To manually install the blocks do

    git clone https://github.com/dilshan/gr-rftap.git
    cd gr-rftap
    mkdir build
    cd build
    cmake ..
    make
    sudo make install
    sudo ldconfig

## Usage, Demos and Further information

See RDS and Wi-Fi flowgraphs in examples/ directory.

See: https://rftap.github.io/
