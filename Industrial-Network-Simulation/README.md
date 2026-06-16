# 🌐 Industrial Network Simulation & Perimeter Defense

A comprehensive network engineering and security architecture project designing and simulating an enterprise-grade industrial computer network. The project models a highly secure, scalable infrastructure connecting multiple corporate departments using Cisco hardware principles.

## 📐 Network Architecture & Topology
The infrastructure is engineered to simulate a real-world enterprise deployment with substantial scale:
* **Scale Metrics:** Comprises **23 Routers**, **17 Switches**, **5 Core Servers**, and **40 End Devices** (PCs and Laptops).
* **Departmental Segmentation (VLANs):** Structured around four distinct corporate business units—**Manufacturing, Supply Chain, IT, and Human Resources**. Localized traffic segmentation is handled via Virtual Local Area Networks (VLANs) to minimize broadcast domains and prevent unauthorized lateral movement.
* **IP Addressing Schema:** Built using systematic IP spacing structures (`126.0.0.1` onwards for end devices and `126.128.0.0` onwards for sub-routed segments) to maintain strict tracking subnetworks.

## 🛡️ Hardened Security & Operational Engineering (SOC Focus)
This simulation maps directly out to Security Operations Center (SOC) defense principles through several infrastructure implementation layers:
* **Perimeter Defense (Firewalls & ACLs):** Deploys dedicated edge firewalls to block external threat vectors. Implements rigorous Access Control Lists (ACLs) to enforce network boundaries, restrict inter-VLAN communications, and establish secure user authentication protocols.
* **Secure Remote Access (VPN):** Configures Virtual Private Networks (VPNs) to ensure remote employees can establish encrypted tunnels back into corporate resources safely from public zones.
* **Core Network Services:** Features fully configured enterprise application nodes including **DHCP Servers** for automated IP distribution, **FTP/TFTP Servers** for data transfer protocols, and dedicated **Web and Data Servers**.
* **Traffic Optimization (QoS):** Employs Quality of Service (QoS) configurations to prioritize critical operational traffic, reduce latency across routed boundaries, and optimize overall system performance under load.

## 🛠️ Technical Stack
* **Simulation Environment:** Cisco Packet Tracer
* **Protocols & Security:** VLAN Tagging, Access Control Lists (ACLs), VPN Tunneling, Network Firewalls, DHCP, FTP/TFTP
* **Traffic Engineering:** Quality of Service (QoS), Relational Subnetting, System Infrastructure Auditing
