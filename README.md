# RISC-V-SoC-Tapeout-
My submission for RISC-V-Reference SoC Tapeout Program(VSD)
Overview

This repository is my Week-0 submission for the RISC-V SoC Tapout Program.
The goal of this week is to:

Create and set up a GitHub repository.

Add a README file describing the environment and tools.

Confirm readiness for future weeks where RTL-to-GDSII design flow will be executed.

📂 Structure

README.md : Documentation of Week-0 task.

src/ : Placeholder for source files (to be added in later weeks).

scripts/ : Placeholder for automation scripts.

.gitignore : Ignore build artifacts.

⚙️ System Configuration

OS Used: Ubuntu 22.04 LTS (64-bit)

Processor: Intel/AMD (x86_64)

RAM: Minimum 8 GB recommended

Installed Tools:

Git

Docker

OpenLANE

Magic VLSI

KLayout

ngspice

🛠️ Installation Steps
1. Install Git
sudo apt update
sudo apt install -y git
git --version

2. Install Docker
sudo apt install -y docker.io
sudo systemctl start docker
sudo systemctl enable docker
docker --version

3. Add User to Docker Group
sudo usermod -aG docker $USER


(Log out and log back in for this to take effect)

4. Verify Docker Access
docker run hello-world

5. Clone OpenLANE
git clone https://github.com/The-OpenROAD-Project/OpenLane.git
cd OpenLane
make

6. Install Magic, KLayout, ngspice
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

🎯 Learning Outcomes (Week-0)

Understood the program flow for RISC-V SoC Tapout.

Successfully created a GitHub repository.

Documented environment and tool installation
