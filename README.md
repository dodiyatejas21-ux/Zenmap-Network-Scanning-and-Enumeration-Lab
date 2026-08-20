# Zenmap-Network-Scanning-and-Enumeration-Lab

## Introduction
Zenmap is the graphical user interface (GUI) for Nmap, a network scanning and security auditing tool. It provides an easy-to-use interface for performing network discovery, port scanning, service and version detection, and OS detection. In this project, Zenmap is used to scan the Metasploitable 2 target in an authorized lab environment and analyze the scan results.

## Objectives
- To understand the basics of Zenmap and GUI-based network scanning.
- To discover active hosts on a network.
- To identify open ports on the target system.
- To detect running services and their versions.
- To identify the operating system of the target machine.
- To analyze and understand Zenmap scan results.
- To gain practical experience with network scanning in an authorized lab environment.

## Requirements
- **Kali Linux** – Used as the main operating system.
- **Zenmap** – Used for GUI-based network scanning.
- **Metasploitable 2** – Used as the target machine.
- **VMware** – Used to create the virtual lab environment.
- **Network Connection** – Required for communication between the virtual machines.
- **Basic Networking Knowledge** – Required to understand IP addresses, ports, and services.

## Step 1: Launch Zenmap and Identify Target
In this step, Zenmap is opened and the IP address of the Metasploitable 2 target machine is entered for scanning.

### Target IP
192.168.126.131

### Steps
1. Open Zenmap from the Applications menu.
2. Enter `192.168.126.131` in the **Target** field.
3. Select **Ping scan** from the **Profile** dropdown.
4. Click the **Scan** button.
5. Wait for the scan to complete and check the result.

### Purpose
To verify that the Metasploitable 2 target machine is active and reachable on the network.

### Expected Result
Zenmap should display that the target host **192.168.126.131 is up**.

### Result
The Metasploitable 2 target was successfully identified and found to be reachable on the network.

<img width="1711" height="740" alt="Screenshot 2026-08-20 132638" src="https://github.com/user-attachments/assets/cf65838c-928c-49f3-a0aa-851cd1a77acb" />

## Step 2: Quick Scan
In this step, Zenmap is used to perform a quick scan of the Metasploitable 2 target to identify commonly used open ports and services.

### Target IP
192.168.126.131

### Profile
Quick Scan

### Steps
1. Open Zenmap.
2. Enter `192.168.126.131` in the **Target** field.
3. Select **Quick Scan** from the **Profile** dropdown.
4. Click the **Scan** button.
5. Wait for the scan to complete.
6. Check the **Nmap Output** and **Ports/Hosts** tabs for the results.

### Purpose
To quickly identify open ports and available services on the target machine.

### Result
The scan displays the open ports and services detected on the Metasploitable 2 target.

### Target
Metasploitable 2 – Authorized Lab Target

<img width="1715" height="820" alt="Screenshot 2026-08-20 133826" src="https://github.com/user-attachments/assets/ba9d3482-7904-4bb7-a187-3573fbd3bb12" />
<img width="1720" height="816" alt="Screenshot 2026-08-20 133843" src="https://github.com/user-attachments/assets/cfb1f63e-65e7-480d-8e71-3d3eb3ce855b" />

