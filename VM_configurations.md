# VM Configurations

This file documents the configuration details of all virtual machines, including OS, resources, network, and purpose.

---

## 1. Domain Controller (DC)
- **Hostname:** project-x-dc
- **OS:** Windows Server 2022 / 2025
- **CPU:** 2 cores
- **RAM:** 4 GB
- **Storage:** 50 GB
- **Network Adapter:** NAT / Internal Network
- **Purpose / Role:**  
  - Domain Controller (Active Directory, DNS, DHCP)  
  - Centralized authentication and domain management

---

## 2. Windows Client
- **Hostname:** project-x-win-client
- **OS:** Windows 11 Enterprise
- **CPU:** 2 cores
- **RAM:** 4 GB
- **Storage:** 40 GB
- **Network Adapter:** NAT / Internal Network
- **Purpose / Role:**  
  - Simulated corporate workstation  
  - Target for attacks and security testing

---

## 3. Linux Client
- **Hostname:** project-x-linux-client
- **OS:** Ubuntu Desktop 22.04 LTS
- **CPU:** 2 cores
- **RAM:** 4 GB
- **Storage:** 40 GB
- **Network Adapter:** NAT / Internal Network
- **Purpose / Role:**  
  - Linux workstation environment  
  - For testing client-side security and administration

---

## 4. Corporate Server
- **Hostname:** project-x-corp-svr
- **OS:** Ubuntu Server 22.04 LTS
- **CPU:** 2 cores
- **RAM:** 4 GB
- **Storage:** 50 GB
- **Network Adapter:** NAT / Internal Network
- **Purpose / Role:**  
  - Backend server / jumpbox  
  - Hosts services needed by clients and attacker VM

---

## 5. Security Workbench
- **Hostname:** project-x-sec-box
- **OS:** Ubuntu Desktop 22.04 LTS
- **CPU:** 2 cores
- **RAM:** 4 GB
- **Storage:** 40 GB
- **Network Adapter:** NAT / Internal Network
- **Purpose / Role:**  
  - Security tools workstation  
  - Monitoring, analysis, and management of lab traffic

---

## 6. Security Sandbox
- **Hostname:** project-x-sec-work
- **OS:** Ubuntu Desktop 22.04 LTS
- **CPU:** 2 cores
- **RAM:** 4 GB
- **Storage:** 40 GB
- **Network Adapter:** NAT / Internal Network
- **Purpose / Role:**  
  - Simulated malware sandbox / monitoring environment  
  - Experimenting safely with offensive security tools

---

## 7. Attacker VM
- **Hostname:** project-x-attacker
- **OS:** Kali Linux 2024.x
- **CPU:** 2 cores
- **RAM:** 4 GB
- **Storage:** 40 GB
- **Network Adapter:** NAT / Internal Network
- **Purpose / Role:**  
  - Offensive security machine  
  - Reconnaissance, exploitation, and attack simulations

---

## Notes
- All VMs are connected via a **NAT/Internal network** to simulate a private enterprise network.
- Snapshots of each VM are recommended before performing attacks to allow safe rollback.
- Resource allocations (CPU, RAM, Storage) are configurable depending on host machine capabilities.
- For additional security exercises, additional tools or scripts can be installed on the Security Workbench and Attacker VM.

---

> This file provides an overview of VM setup and can be used to reproduce the lab or explain it during an interview.

