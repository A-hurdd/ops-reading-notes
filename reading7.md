# Reading Notes 07

## Network Connectivity
### Agenda
Review of previous class

Remote Connectivity

Network Protocols
> TCP/IP Model
> IP adress configuration

Network Ports
> SSH
> RDP
> SCP

Demo

Lab
---
### Our Lab Plan
Acess lab PC from personal computer Secure Shell (SSH)
> port 22

Secure Copy Protocol (SCP)
> port 22

Microsoft Remote Desktop Protocol (RDP)
> port3389
---
### Network Protocols

A protocol is a set of agreed upon rules to facilitate communication.
> The Internet Protocol (IP) facilitates the routing and adressing of data packets to reach their destination.

An IP afress is the "location" (mailing adress) of a computer.

TCP-IP Model depicts four "Layers" of computer networking.
![image](https://github.com/A-hurdd/ops-reading-notes/assets/154618317/1b2ea9d7-ddaa-48d2-bb44-7df70bbd3f4e)
---
### IP Adress Configuration
A dynamic IP adress is what most hosts recieve from DHCP server when connecting to a network.
> Lease time
> Can change (be"lost")

A static IP adress is configured on the host itself
> Never changes but can cause IP conflicts

A reserved IP adress is achieved by associating an IP adress to a MAC adress on the DHCP server.

 ### What is a DHCP?
 DHCP stands for Dynamic Host Configuration Protocol

 Client-server model

 Simplified overview of how DHCP works:
 > Discover
> Offer
> Request
> Acknowledgement
> Lease


