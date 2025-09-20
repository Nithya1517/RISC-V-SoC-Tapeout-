# RISC-V-SoC-Tapeout-
My submission for RISC-V-Reference SoC Tapeout Program(VSD)

# **Overview**

This repository is my Week-0 submission for the RISC-V SoC Tapout Program.
The goal of this week is to:

Create and set up a GitHub repository.

Add a README file describing the environment and tools.

Confirm readiness for future weeks where RTL-to-GDSII design flow will be executed.

 #  __Structure__

README.md : Documentation of Week-0 task.

src/ : Placeholder for source files (to be added in later weeks).

scripts/ : Placeholder for automation scripts.

.gitignore : Ignore build artifacts.

⚙️ __System Configuration__

OS Used: Ubuntu 22.04 LTS (64-bit)

Processor: Intel/AMD (x86_64)

RAM: Minimum 8 GB recommended

__Installed Tools:__

Git

Docker

OpenLANE

Magic VLSI

KLayout

ngspice

__🛠️ Installation Steps__

__1. Install Git__
sudo apt update
sudo apt install -y git
git --version

__2. Install Docker__
sudo apt install -y docker.io
sudo systemctl start docker
sudo systemctl enable docker
docker --version

__3. Add User to Docker Group__
sudo usermod -aG docker $USER


(Log out and log back in for this to take effect)

__4. Verify Docker Access__
docker run hello-world

__5. Clone OpenLANE__
git clone https://github.com/The-OpenROAD-Project/OpenLane.git
cd OpenLane
make

__6. Install Magic, KLayout, ngspice__
sudo apt install -y magic klayout ngspice

🚀 Getting Started

Clone this repository

git clone https://github.com/<your-username>/RISC-V-SoC-Tapout.git
cd RISC-V-SoC-Tapout


Verify environment setup

Docker should run without sudo

Tools should be available in PATH:

magic -version
klayout -version
ngspice -v

__🎯 Learning Outcomes (Week-0)__

Understood the program flow for RISC-V SoC Tapout.

Successfully created a GitHub repository.

Documented environment and tool installation
