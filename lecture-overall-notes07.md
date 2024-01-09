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

All that DHCP does is assign and reassign IP adresses to devices. So that it can be found on your private network.

### Network Ports
Network ports are like numbered doorways into a computer system.
> Every data packet must designate a source and destination port
> Open Ports permit traffic
> Closed ports blocks traffic

Port numbers range from 0 to 65535.
> Well known ports (0-1023) are assigned and controlled but can be registered to prevent duplication.
> Dynamic/private ports (1024-65535) are not assigned,controlled, or registered.

SSH- port 22
RDP- port 3389
HTTP- port 80
HTTPS- port 43

### SSH 
Secure Shell (SSH) is a modern standard for remoter terminal acess. It is a text only GUI.
SSH can use password authentication to establish a terminal-only connection to a computer running the SSH service.
As stated above SSH uses port 22.
<amy applications such as WinSCP and VSCode can "piggyback" SSH by using it as a background means of transferring data.

### RDP
> Microsoft Remote Desktop Protocol (RDP) is built into microsoft windows.

Uses TCP prt 3389.
Not known for greatest security, but within a LAN like our home it's fine.
Can be used by macOS id installed seperately.
XRDP is a software installed to Ubuntu Linux Desktop to act as a RDP server.
Allows windows/macOS clients to connect via RDP.
