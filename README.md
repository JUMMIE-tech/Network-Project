Netcore Solutions Network using Cisco Packet Tracer

A Cisco Packet Tracer project that builds and configures the complete Netcore Solutions Network across three departments. The project covers network topology setup, IP addressing, router configuration, DHCP relay, connectivity testing, and access control using an ACL.


Table of Contents
Project Overview
Network Topology
Tools and Technologies
Configuration Steps
Results and Findings
Author


Project Overview
The purpose of this project was to build the Netcore Solutions Network in Cisco Packet Tracer and configure communication between three departments.

The project involved:
Creating the complete network topology.
Configuring 1 Cisco 2911 router, 3 Cisco 2960 switches, 6 PCs, and 1 server.
Assigning IP addresses and default gateways to network devices.
Configuring router interfaces with the appropriate subnet addresses.
Relaying DHCP to PCs in the other departments.
Testing connectivity between all departments.
Applying an Access Control List (ACL) to restrict HR from accessing the Admin department while allowing other traffic.


Network Topology

The network consists of three departments connected through a central router and switches.
Router: 1 × Cisco 2911
Switches: 3 × Cisco 2960
PCs: 6 total, with 2 PCs per department
Server: 1 server located in the Admin department
Departments: Admin, Sales, and HR
All devices were connected using the appropriate network cables.
IP addresses were manually assigned to the Admin PC configuration.
The Admin department uses the 192.168.10.0/24 network.
The HR department uses the 192.168.30.0/24 network.
The HR department was configured so that it could not access the Admin department after the ACL was applied.


Tools and Technologies
Cisco Packet Tracer
Cisco 2911 Router
Cisco 2960 Switches
PCs
Server
Ethernet/network cables
IP addressing
DHCP relay
Ping
Access Control List (ACL)


Configuration Steps
Build the complete Netcore Solutions Network topology in Cisco Packet Tracer.
Place 1 Cisco 2911 router, 3 Cisco 2960 switches, 6 PCs, and 1 server in the topology.
Connect all devices using the correct cables.
Assign IP addresses to the network devices and configure the router interfaces with the appropriate subnet addresses.
Configure the appropriate default gateway on each device.
Manually enter the required static IP configuration on the Admin PC.
Configure and verify the router interfaces.
Configure DHCP relay so that PCs in the other departments can receive the required network configuration.
Test basic connectivity by running ping tests between the three departments.
Verify that all devices can communicate before applying network restrictions.
Configure an ACL on the router to prevent the HR network, 192.168.30.0/24, from reaching the Admin network, 192.168.10.0/24.
Keep other network traffic allowed while applying the restriction.
Validate the ACL by performing ping tests between departments.
Confirm that HR cannot reach the Admin IP address 192.168.10.11.
Confirm that communication between HR and Sales remains functional.


Results and Findings

All network cables were connected correctly.
The router interfaces were successfully configured.
Connectivity testing was successful with 0% packet loss before the ACL was applied.
DHCP relay was configured for PCs in the other departments.
The ACL successfully prevented the HR department from accessing the Admin department.
A ping from the HR department to Admin IP 192.168.10.11 resulted in 100% packet loss, confirming that the restriction was working.
HR could still communicate with other permitted IP addresses, including the Sales department.
The completed Packet Tracer topology provided a working model that could be used as a basis for implementing the network in a real-life environment.


Author
Olajumoke Olaniyan
