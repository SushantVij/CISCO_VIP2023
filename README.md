# CISCO_VIP2023
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/9af7f32a-f6d1-4029-be1a-e6a163f4e5c8)
# Problem Statement 
Choose a university/college campus and analyze its network topology. Map the network using Cisco Packet Tracer and identify the security
controls that are in place, such as network segmentation, intrusion detection systems, firewalls, and authentication and authorization systems. Apply the knowledge
gained from the NetAcad cyber security course to conduct an attack surface mapping, aiming to identify potential entry points for cyber-attacks. Propose
countermeasures to mitigate these risks.
Tasks:
1. Campus Network Analysis: Choose a university or college campus and conduct an analysis of its existing network topology, including the layout, devices, and
connections.
2. Network Mapping: Utilize Cisco Packet Tracer to map the network infrastructure, representing the placement and interconnectivity of routers, switches, firewalls, and
other relevant network components.
3. Attack Surface Mapping: Conduct an attack surface mapping exercise to identify potential vulnerabilities and weaknesses within the network architecture and design,
considering factors such as unauthorized access, data breaches, and network availability.
4. Secure Access Controls: Incorporate appropriate security controls (e.g., VLANs, IDP/IPS, VPN, Firewalls, password management, vulnerability management etc.) in
your design to enhance security posture.
Deliverables:
1. Network topology diagram depicting the existing infrastructure and attack surface findings.
2. Security assessment report highlighting identified security risks, proposed solutions, and countermeasures to mitigate attack surface risks.


# Work Done
1.	Software and hardware requirements

Prior to proceeding with the implementation, it is essential to ensure that the following requirements are met:

A suitable workstation, preferably a mid-high range laptop, is available for use.
Packet Tracer software by Cisco is installed on the workstation.
The workstation has a minimum of 8 GB RAM for smooth performance.
A processor with a CPU Mark score of 10,000 or higher is recommended.
There should be at least 16 GB of dedicated hard disk space available on the workstation.
The workstation should have a USB 3.0+ port for compatibility with external devices.


2.	Brief knowledge about our approach

The wireless network designed for the university campus has been successfully implemented. To visualize and test the network, we utilized Cisco Packet Tracer, a powerful simulation tool that allows users to experiment with their projects. The integration of a wireless network in the educational campus has significantly enhanced accessibility to educational resources for both teachers and students. It has established a crucial platform for seamless information exchange and communication within the campus community.

3)Network Requirements
The wireless university network is based on the outline of Thapar University in Patiala, and it is divided into two main areas:

1. Campus Area:
The campus area is subdivided into different access points, including:
   - CSED LAB building
   - Library
   - LP and LT
   - Other branches Server Center
   - Registry office
   - Accounts office
  
   - Devices Used for The Network
   - ![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/36d4689a-be9b-4f8d-8583-3b963474e95b)
  
   # Implementation and Flow Diagram
   To design the wireless network for the university, we began by placing the core devices in the designated locations on the layout.

1. Main Router: Positioned at the center of the university outline, the main router serves as the central hub. It is connected to the server switch using a gigabit ethernet port and copper straight-through cable. Additionally, it connects to sub routers, namely the campus router and hostel router, using the serial port and serial DCE cable, respectively, in the campus and hostel areas.

2. Server Switch: The server switch is linked to the main router and connected to the EMAIL, DNS, and WEB servers.

3. Campus Router: Connected to the campus switch, the campus router further connects to the wireless access points in different academic blocks, such as LP and LT, various branch classes like CSED LAB, library, and LP and LT. These wireless access points facilitate connections to computing devices like PCs, laptops, and smartphones.

4. Hostel Router: The hostel router is connected to the hostel switch and, in turn, connected to the wireless access points in Boys' and Girls' blocks. These access points provide secure access, requiring passwords to connect computing devices in each area.

All connections within the network are established using ethernet ports, such as gigabit ethernet and fast ethernet, and copper straight-through cables.
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/11973d23-e274-4f8d-84fa-05d7fdb91fe4)

# 	Configuring IP Addresses
Main Router configuration
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/8ebbc2c4-b902-4bd2-aec4-846eb269ad1c)
GigabitEthernet0/1
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/bd2aa688-4ce9-4d33-a165-18a4cb31bccc)
Serial0/1/0
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/75c23d42-bae5-42f0-a2fb-6199a2407336)
Serial0/1/1
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/74105e8b-71b4-4ee3-aa57-0461b9ccc431)
RIP 
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/899a167d-7af7-47b9-87cc-37a2070abda5)


●	DNS SERVER
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/8eb4a0a6-7df0-4d38-bac8-db5e391c4187)
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/e6202d77-7c82-4c53-9cfd-f52b76a2911f)


●	WEB SERVER
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/c5ad1808-0823-422e-be78-b9df43e43a8a)
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/bdf48b84-d4f3-479a-bd5a-02ee67fdd5ec)

●	EMAIL SERVER
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/8ea4f30f-ae4f-4a74-8a77-ca238eea67e8)
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/82b49c28-6706-4f47-a8d3-683bead9fdb2)

# NETWORK TOPOLOGY
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/5243500f-68e0-4892-a09e-6daace35ee7b)
SIMULATION
![image](https://github.com/SushantVij/CISCO_VIP2023/assets/116457738/0ab6d808-e74e-4ba3-9fdb-edc3c2bdf082)



















