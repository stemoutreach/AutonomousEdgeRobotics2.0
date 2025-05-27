# Pi500 Setup Guide

This guide provides step-by-step instructions to set up the Pi500 for the Autonomous Edge Robotics 2.0 project. Follow these steps to prepare your Pi500 for development and testing.

---

## Table of Contents

1. [Prerequisites](#1-prerequisites)
2. [Hardware Setup](#2-hardware-setup)
3. [Software Installation](#3-software-installation)
4. [Network Configuration](#4-network-configuration)
5. [Testing the Setup](#5-testing-the-setup)
6. [Troubleshooting](#6-troubleshooting)

---

## 1. Prerequisites

Before you begin, ensure you have the following:

- **Pi500 Board**: The main development board.
- **MicroSD Card (32GB or higher)**: For the operating system.
- **MicroSD Card Reader**: To flash the OS onto the card.
- **Power Supply (5V/3A)**: To power the Pi500.
- **HDMI Cable and Monitor**: For initial setup.
- **USB Keyboard and Mouse**: For input during setup.
- **Ethernet Cable or Wi-Fi Dongle**: For network connectivity.

---

## 2. Hardware Setup

1. **Insert MicroSD Card**: Place the MicroSD card into the card reader connected to your computer.

2. **Flash Operating System**:
   - Download the latest Raspberry Pi OS from the [official website](https://www.raspberrypi.org/software/).
   - Use [Balena Etcher](https://www.balena.io/etcher/) to flash the OS onto the MicroSD card.

3. **Assemble the Pi500**:
   - Insert the flashed MicroSD card into the Pi500.
   - Connect the HDMI cable to a monitor.
   - Plug in the USB keyboard and mouse.
   - Connect the Ethernet cable or Wi-Fi dongle.
   - Finally, connect the power supply to boot up the Pi500.

---

## 3. Software Installation

1. **Initial Boot**:
   - Upon first boot, follow the on-screen instructions to set up the Raspberry Pi OS.
   - Configure language, time zone, and create a user account.

2. **Update System Packages**:
   ```bash
   sudo apt update && sudo apt upgrade -y
   ```

3. **Install Necessary Software**:
   - Install Git:
     ```bash
     sudo apt install git -y
     ```
   - Clone the Autonomous Edge Robotics 2.0 repository:
     ```bash
     git clone https://github.com/stemoutreach/AutonomousEdgeRobotics2.0.git
     ```

---

## 4. Network Configuration

1. **Wi-Fi Setup** (if using Wi-Fi):
   - Click on the network icon in the top-right corner.
   - Select your Wi-Fi network and enter the password.

2. **SSH Access** (optional):
   - Enable SSH:
     ```bash
     sudo systemctl enable ssh
     sudo systemctl start ssh
     ```
   - Find the Pi500's IP address:
     ```bash
     hostname -I
     ```
   - You can now SSH into the Pi500 from another device:
     ```bash
     ssh pi@<IP_ADDRESS>
     ```

---

## 5. Testing the Setup

1. **Navigate to Test Directory**:
   ```bash
   cd AutonomousEdgeRobotics2.0/ConnectAndTest
   ```

2. **Run Test Scripts**:
   - Execute the provided test scripts to ensure all components are functioning correctly.
   - For example:
     ```bash
     python3 test_motors.py
     ```

3. **Verify Output**:
   - Ensure that the motors respond as expected.
   - Check sensor readings and other peripherals.

---

## 6. Troubleshooting

- **No Display Output**:
  - Ensure the HDMI cable is securely connected.
  - Try a different monitor or cable.

- **Wi-Fi Not Connecting**:
  - Double-check the Wi-Fi credentials.
  - Ensure the Wi-Fi dongle is compatible.

- **SSH Connection Refused**:
  - Confirm that SSH is enabled.
  - Verify the IP address.

- **Hardware Not Responding**:
  - Check all physical connections.
  - Ensure the correct GPIO pins are used.

---

For further assistance, refer to the [Autonomous Edge Robotics 2.0 GitHub repository](https://github.com/stemoutreach/AutonomousEdgeRobotics2.0) or contact the project maintainers.
