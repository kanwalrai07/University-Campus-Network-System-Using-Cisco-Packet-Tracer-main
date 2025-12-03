# University-Campus-Network-System-Using-Cisco-Packet-Tracer-main
Campus Network System Using Cisco Packet Tracer  This project demonstrates the design and simulation of a robust campus network for City University, which consists of two campuses located 80 miles apart. It utilizes Cisco Packet Tracer to simulate network topologies, VLAN configurations, and dynamic routing protocols.


📖 Project Overview

The goal of this project is to connect two distinct campuses—Main Campus and City Campus—while ensuring efficient communication, logical segmentation, and dynamic IP allocation for various faculties and departments.

🎯 Objectives

Configure a multi-campus network topology.

Implement VLANs (Virtual Local Area Networks) to group devices logically rather than physically.

Configure RIPv2 (Routing Information Protocol) for dynamic routing between networks.

Establish DHCP services on routers for dynamic IP assignment.

🏢 Network Scenario

The network is designed for City University, which supports staff and students distributed across four faculties.

1. Main Campus

Building A:

Administrative Staff (Management, HR, Finance).

Faculty of Business.

Building B:

Faculty of Engineering and Computing.

Faculty of Art and Design.

Building C:

Students' Lab.

IT Department (hosts the University Web Server and other servers).

2. City Campus

Faculty of Health and Sciences: Staff and students situated on separate floors.

⚙️ Technical Features & Configuration

VLAN Implementation: Used to separate departments/faculties into their own IP networks for security and traffic management.

Dynamic Routing (RIPv2): Configured to allow communication between the two geographically distant campuses (AD value of 120, port 520).

DHCP Server: Routers are configured to provide Dynamic IP addresses to end devices (PCs, Printers).

Security: Basic switch security settings applied.

🛠️ Components Used

The simulation was built using the following Cisco devices in Packet Tracer:

Component

Quantity

Model

Routers

3

Cisco 2911

L3 Switches

2

Cisco 3650-24PS

Switches

10

Cisco 2960

Servers

3

Server-PT

End Devices

~19

PCs and Printers

🚀 How to Run

Install Packet Tracer: Ensure you have Cisco Packet Tracer installed (compatible with .pkt files).

Download: Clone this repository or download the Final_Project_CampusNetwork.pkt file.

Open: Launch the .pkt file in Cisco Packet Tracer.

Simulate:

Use the Simulation Mode to observe packet flow (ICMP, DHCP, RIP packets).

Open a PC terminal and try ping to test connectivity between Building A and the City Campus.

Check Router configs using the CLI tab.

📂 File Structure

├── Final_Project_CampusNetwork.pkt  # The main simulation file
└── README.md                        # Project documentation


This project was created for educational purposes to demonstrate networking concepts such as VLANs, Inter-VLAN routing, and RIPv2.
