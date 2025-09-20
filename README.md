# SAI_VSD
Vlsi 
This repository documents the setup and installation of open-source VLSI tools as part of the SAI_vsd program.
# 🚀 RISC-V SoC Tapeout Program — Week 0 Setup & Tools  
*Author:V sai charan reddy
## 🛠 Foundation Week: Environment Setup and Tool Installation  
This week focused on preparing the development environment with essential open-source EDA tools for the complete RTL-to-GDSII flow.  

---

## ✅ Tasks Overview  

| Task   | Description                  | Status |
|--------|------------------------------|--------|
| Task 0 | Complete EDA Toolchain Setup | ✅ Done |

---

## 📦 Tools Installed in Week 0  

### 🔹 Core RTL Design & Synthesis Tools  

| Tool    | Purpose                          | Verification |
|---------|----------------------------------|--------------|
| Yosys   | RTL Synthesis & Logic Optimization | ✅ Verified |
| Iverilog| Verilog Simulation & Compilation | ✅ Verified |
| GTKWave | Waveform Viewer & Analysis       | ✅ Verified |
| Ngspice | Analog & Mixed-Signal Simulation | ✅ Verified |
| Magic VLSI | Layout Design & DRC Verification | ✅ Verified |

### 🔹 Advanced Flow Tools  

| Tool   | Purpose                      | Verification |
|--------|------------------------------|--------------|
| Docker | Containerization Platform    | ✅ Verified |
| OpenLane | Complete RTL-to-GDSII Flow | ✅ Verified |

---

## 🌟 Key Learnings  

- Installed and verified open-source EDA tools ecosystem  
- Mastered environment setup for RTL design and synthesis workflows  
- Prepared a comprehensive system for RTL → GDSII experiments  
- Established Docker-based OpenLane environment for automated design flows  
- Configured VM with optimal specifications for EDA workloads  

---

## 🎯 Program Objectives & Scope  

| Aspect       | Details |
|--------------|---------|
| 🎓 Learning Path | Complete SoC Design: RTL → Synthesis → Physical Design → Tapeout |
| 🛠 Tools Focus | Open-Source EDA Ecosystem (Yosys, OpenLane, Magic, etc.) |
| 🏭 Industry Relevance | Real-world semiconductor design methodologies |
| 🤝 Collaboration | Part of India's largest RISC-V tapeout initiative |
| 📈 Scale | 3500+ participants contributing to silicon advancement |
| 🇮🇳 National Impact | Advancing India's semiconductor ecosystem |

---

## 🙏 Acknowledgment  

Special thanks to Kunal Ghosh and the VLSI System Design (VSD) Team for leading and supporting the RISC-V SoC Tapeout Program.  

---

## 📈 Weekly Progress Tracker  

- ✅ Week 0: Environment Setup & Tools  
- 🔜 Upcoming: RTL design, synthesis, physical design & final tapeout preparation  

---

## 🖥 System Requirements  

- 6 GB RAM  
- 50 GB HDD  
- Ubuntu 20.04 or higher  
- 4 vCPU  

---

## ⚙ Tool Installation Commands  

### 🔹 General Setup  
`bash
sudo apt update  
sudo apt install build-essential dkms linux-headers-$(uname -r)  
cd /media/spatha/VBox_GAs_7.1.8/  
./autorun.sh
sudo apt-get update  
git clone https://github.com/YosysHQ/yosys.git  
cd yosys  
sudo apt install make build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev  

make config-gcc  
git submodule update --init --recursive  
make  
sudo make install
sudo apt-get update  
sudo apt-get install iverilog
sudo apt-get update  
sudo apt install gtkwave
