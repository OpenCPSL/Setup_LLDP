# setup_lldp.sh

This script, `setup_lldp.sh`, is a simple utility designed to install, configure, and enable the Link Layer Discovery Protocol (LLDP) on network interfaces for Linux systems.  LLDP is a network protocol used to identify and announce devices and their network topology.  This script automates the process of installing `lldpad` and `lldpd`, then enables LLDP on each available Ethernet interface.  

This setup is especially useful on Raspberry Pi or other devices where identifying network links and configurations can simplify management and troubleshooting.

---

## Prerequisites

- **Operating System**: This script is designed for Debian-based Linux distributions (e.g., Ubuntu, Raspberry Pi OS).
- **Root Privileges**: Run the script with elevated privileges as it installs packages and modifies network settings.

---

## Installation and Usage

### 1. Make the Script Executable

After downloading or cloning the script, modify the permissions to allow execution:

```bash
sudo chmod +x setup_lldp.sh
```

### 1. Run the Script Executable

```bash
./setup_lldp.sh
```
