# Cybersecurity Homelab  

## Overview  
This homelab simulates a realistic enterprise environment to practise system administration, network architecture, attack simulation, and defense monitoring inside virtual machines. It demonstrates hands-on cybersecurity skills and understanding of both offensive and defensive operations.

## Environment Architecture & Topology  

| Hostname (VM)            | Purpose / Role                                      |
|--------------------------|----------------------------------------------------|
| `project-x-dc`           | Domain Controller – DNS, DHCP, Active Directory  |
| `project-x-win-client`   | Windows workstation / corporate client           |
| `project-x-linux-client` | Linux client / desktop environment                |
| `project-x-corp-svr`     | Corporate server / backend services               |
| `project-x-sec-box`      | Security workbench / security tools server       |
| `project-x-sec-work`     | Security monitoring / sandbox environment        |
| `project-x-attacker`     | Attacker VM: penetration testing and simulations |

The lab uses a NAT-based virtual network to simulate an isolated enterprise environment, enabling controlled testing and interaction among all VMs.

## Tools & Technologies  

**Defensive / Infrastructure:**  
- Active Directory, DNS, DHCP  
- SIEM / monitoring tools  
- Email and network services  

**Offensive / Pentesting:**  
- Windows and Linux post-exploitation tools  
- Brute-force / dictionary attack tools  
- Reconnaissance and exploitation scripts  

## Lab Modules & Activities  

Typical exercises in the lab include:  
1. Provisioning and configuring VMs  
2. Deploying infrastructure services (domain controller, backend servers, workstations)  
3. Configuring defensive monitoring and logging  
4. Creating intentionally vulnerable services for attack simulation  
5. Performing controlled attacks (reconnaissance, exploitation, lateral movement)  
6. Analyzing logs, alerts, and performing incident response  

## Skills Demonstrated  
- Infrastructure and network design in virtualized environments  
- System administration (Windows & Linux)  
- Deployment of security tools and monitoring solutions  
- Offensive security: vulnerability exploitation, lateral movement, privilege escalation  
- Defensive security: log analysis, detection, incident simulation  
- Practical application of real-world attack and defense scenarios  
