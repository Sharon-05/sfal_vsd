# sfal_vsd
# Day 0 - Tools Installation

## Task 1: Create GitHub Repository and Document Summary
Created this GitHub repository to document the installation process and tool summaries for the VSD course.

## Task 2: Install Tools and Update GitHub with Tool Snapshots
Followed the installation instructions to set up the required tools. Snapshots of the successful installations are provided below.

### Tool Installation Guide

#### 2. Yosys (Verilog RTL Synthesis Tool)
```bash
sudo apt-get update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make
sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make
sudo make install

<img width="782" height="103" alt="Screenshot from 2025-09-20 23-06-42" src="https://github.com/user-attachments/assets/41dad6e7-f4eb-4bd5-b994-7cf5a0ce8dca" />
```bash
### 3. Icarus Verilog (iverilog) (Verilog Simulation Tool)
sudo apt-get update
sudo apt-get install iverilog

<img width="786" height="237" alt="image" src="https://github.com/user-attachments/assets/4a201953-468f-491d-a14f-bec6464a410a" />
<img width="782" height="777" alt="image" src="https://github.com/user-attachments/assets/170025e1-d31d-436b-beea-4fece5f67206" />
<img width="782" height="777" alt="image" src="https://github.com/user-attachments/assets/21f2621b-f9ea-4b47-b824-b57f77a2d85b" />
```bash
### 4.GTKWave (Waveform Viewer)
sudo apt-get update
sudo apt install gtkwave

<img width="798" height="223" alt="image" src="https://github.com/user-attachments/assets/e7f61c33-ac7f-4cf1-9097-84ce7081816e" />



