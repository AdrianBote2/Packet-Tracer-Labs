# Packet Tracer Labs

A collection of Cisco Packet Tracer labs built while studying for CompTIA Network+, documenting network design, configuration, and troubleshooting skills.

## Summary

| Lab | Topic |
|---|---|
| [Lab 01](#lab-01---basic-network-topology) | Basic Network Topology |
| [Lab 02](#lab-02---network-topology-wiring) | Network Topology Wiring |
| [Lab 03](#lab-03---osi-model) | OSI Model |
| [Lab 04](#lab-04---basic-cli) | Basic CLI |
| [Lab 05](#lab-05---analyzing-ethernet-switching) | Analyzing Ethernet Switching |
| [Lab 06](#lab-06---configuring-ip-addresses) | Configuring IP Addresses |
---

## Lab 01 - Basic Network Topology

<img width="1174" height="518" alt="Basic Network Topology Lab - 1" src="https://github.com/user-attachments/assets/ab50a3a1-eefe-41e3-bc32-49be9dae8c53" />

### Objective
Getting used to both understanding the hardware (end and server devices) and their purpose. Also understanding how they all connect with one another.

### Topology Design
- Devices used: 2 PCs, 2 Switches, 2 Firewalls, 3 Routers, 2 Servers, 1 Laptop (Attacker)
- The topology was laid out this way to display how a typical network structure would look like.

### What I learned
- Firewalls can be either inside or outside of LAN (Local Area Networks)
- Switches are the connection between devices in a LAN
- How to structure a Network topology

---

## Lab 02 - Network Topology Wiring

<img width="1174" height="518" alt="Proper Cabling Usage Lab - 2" src="https://github.com/user-attachments/assets/16eef3cb-4ddd-4748-a497-9725aed9ff92" />

### Objective
Properly connect devices with correct connections consisting of copper straight-through, copper cross-over, Single Mode Fiber, and Multi Mode Fiber.

### Topology Design
- Devices used: 3 PCs, 1 Server, 8 Switches, 4 Routers
- The design is a network structure that shows the need for different types of cables for different purposes, such as distance, cost, and cross-over issues.

### What I learned
- Connection interference can occur when two similar devices connect with one another, specifically receiving and transmitting bits between similar devices.
- Some devices require accommodation with cross-over cables based on whether they have Auto MDI-X or not.
- Fiber cables are faster than copper cables and can be longer without any issues.

---

## Lab 03 - OSI Model

<img width="1174" height="518" alt="OSI Model - Lab 03" src="https://github.com/user-attachments/assets/0e752ca3-a535-4894-a0d9-d0f684daea63" />

### Objective
Simulating the OSI Model to under stand the process step by step through various devices.

### Topology Design
- Devices used: 1 Server, 2 Routers, 2 Switches, 1 PC

### What I learned
- Each Purpose of the OSI Model and TCP/IP Layers and its purpose of communicating from one device to another
- Encapsulation and Decapsulation is the process of each layer either receiving or building a message usually it comes in the opposite way for proper translation

---

## Lab 04 - CLI (Command Line Interface)

<img width="1174" height="518" alt="CLI - Lab 04" src="https://github.com/user-attachments/assets/e07075b0-dca1-468a-b26c-cd699747e486" />


### Objective
Learn basic CLI commands.

### What I learned
- Creating a Cisco password with both secret and password command.
- secret command has a stronger hash than the password command.
- config files can save previous states of the CLI
- How to properly secure privilege access and how to utilize privilege access for creating files.

---

## Lab 05 - Analyzing Ethernet Switching 

<img width="1920" height="1032" alt="Analyzing Ethernet Switching - Lab 05" src="https://github.com/user-attachments/assets/13b9593d-811b-4f27-b59a-9dd5b57c4fbc" />

### Objective
Ping and understand how Mac addresses help with finding devices through switches.

### Topology Design
- Devices used: 4 PCs, 2 Switches
- Basic LAN design with 2 switches and 4 PCs.

### What I learned
- The step by step process of MAC address tabling
- How ICMP works after completion of finding the device
- The difference and purpose of both unicast and broadcast

---
## Lab 06 - Configuring IP Addresses

**Part 1: Configuring IP Addresses**

<img width="600" alt="Configuring IP Addresses - LAB 06 p1" src="https://github.com/user-attachments/assets/759ebe39-4f50-4c61-a115-5c8fd67ba443" />

**Part 2: Configuring IP Addresses (continued)**

<img width="600" alt="Configuring IP Addresses - LAB 06 p3" src="https://github.com/user-attachments/assets/ecf1b704-0d7e-4352-8b5c-c8ec74d6e095" />

**Part 3: Pinging other devices connected to the router**

<img width="600" alt="Pinging other Devices connected to the router - LAB 06 p2" src="https://github.com/user-attachments/assets/8ff447f6-acbd-41de-8eb4-2a3b9446f6b2" />

### Objective
Manually configuring and troubleshooting any connectivity issues to connect devices from different LANs.

### Topology Design
- 3 LANs, 1 Router, 3 Switches, 3 PCs  
- The design has 3 Local Area Networks which are used to visualize how routers and switches work together in the networking and how packets are sent across networks.

### What I learned
- Configuring devices over local networks and allowing devices to send packets to other devices in different LANs.
- Pinging and troubleshooting configuration issues.
---
