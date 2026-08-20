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

## Step 3: Intense Scan
In this step, Zenmap is used to perform an intense scan to collect detailed information about the Metasploitable 2 target.

### Target IP
192.168.126.131

### Profile
Intense Scan

### Steps
1. Open Zenmap.
2. Enter `192.168.126.131` in the **Target** field.
3. Select **Intense Scan** from the **Profile** dropdown.
4. Click the **Scan** button.
5. Wait for the scan to complete.
6. Review the **Nmap Output** and **Ports/Hosts** tabs.

### Purpose
To collect detailed information about open ports, running services, service versions, and the operating system.

### Result
The Intense Scan provides detailed information about the Metasploitable 2 target and its running network services.

### Target
Metasploitable 2 – Authorized Lab Target

<img width="1919" height="869" alt="Screenshot 2026-08-20 135106" src="https://github.com/user-attachments/assets/b11c19eb-1993-4a4a-8fac-ec5ba31ced55" />
<img width="1905" height="865" alt="Screenshot 2026-08-20 135526" src="https://github.com/user-attachments/assets/bf6e2d0c-235f-45f8-8ae7-a2bad31b2510" />
<img width="1919" height="870" alt="Screenshot 2026-08-20 135647" src="https://github.com/user-attachments/assets/acbc8963-21c3-4037-9a9b-1622f3c65a88" />
<img width="1912" height="867" alt="Screenshot 2026-08-20 135828" src="https://github.com/user-attachments/assets/a18f2174-636f-4b26-9109-7c8aad9fb6d3" />
<img width="1914" height="862" alt="Screenshot 2026-08-20 140101" src="https://github.com/user-attachments/assets/0b83f719-9a9c-42a2-876a-dc5952daa00a" />
<img width="1917" height="873" alt="Screenshot 2026-08-20 140315" src="https://github.com/user-attachments/assets/6d9ec41d-52cb-4b5c-a1ca-517c5ccdac62" />
<img width="1915" height="426" alt="Screenshot 2026-08-20 140452" src="https://github.com/user-attachments/assets/0a44d5dd-2525-4066-b3a4-ce987169ee96" />
<img width="1910" height="866" alt="Screenshot 2026-08-20 140824" src="https://github.com/user-attachments/assets/16c7f31f-fa2f-4cdb-a946-2c13bb3403e2" />

## Step 4: OS Detection
In this step, Zenmap is used to identify the operating system of the Metasploitable 2 target machine.

### Target IP
192.168.126.131

### Profile
OS Detection

### Command
nmap -O 192.168.126.131

### Steps
1. Open Zenmap.
2. Enter `192.168.126.131` in the **Target** field.
3. Select the OS detection profile or use the command `nmap -O 192.168.126.131`.
4. Click the **Scan** button.
5. Check the **Nmap Output** tab for OS information.

### Purpose
To identify the operating system running on the target machine.

### Result
Zenmap attempts to identify the operating system and provides the detected OS information.

### Target
Metasploitable 2 – Authorized Lab Target

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/91734b53-36ca-4e50-ae37-561ff8be5695" />




