# Computer Networks Lab

This repository contains a collection of practical experiments and simulations related to Computer Networks, implemented using Java, TCL (for NS2), and basic networking tools on Windows.

# 🔬 Lab Experiments Covered
No.	Experiment Description
1.	Basic Networking Commands (ipconfig, netstat, nslookup, ping, tracert)
2.	HTTP Web Client to Download a Web Page using TCP Socket
3a.	Echo Server and Client using Java Sockets
3b.	Simple Chat Application using TCP
3c.	File Transfer between Client and Server
4.	DNS Simulation using UDP Sockets
5.	Use of Wireshark to Capture and Analyze Packets
6a.	Simulation of ARP Protocol
6b.	Simulation of RARP Protocol
7.	Congestion Control Simulation using NS2
8.	TCP/UDP Performance Simulation using NS2
9a.	Distance Vector Routing Algorithm
9b.	Link State Routing Algorithm
10.	CRC Error Detection Algorithm Simulation

🛠 Technologies Used
Java (Networking API)

NS2 (Network Simulator 2)

TCL Scripting

Wireshark (Packet Capture Tool)

Windows Command Line Tools

📂 Directory Structure

CN-LAB/
├── JavaPrograms/ 
# Java code for socket programming, DNS, file transfer
├── NS2Simulations/
# TCL files for congestion, TCP/UDP performance
├── Wireshark/ 
# Wireshark screenshots or logs (if any)
├── Report/  
# CN LAB.docx or individual experiment reports
└── README.md 
# This file

⚙️ How to Run
Java Programs
Compile:


javac FileName.java
Run:


java FileName
Note: Ensure both server and client are run from separate terminals for socket-based programs.

NS2 Simulations
Make sure NS2 is installed and configured:


ns filename.tcl
nam output.nam   # To visualize
Wireshark
Open Wireshark.

Start capture on the desired network interface.

Perform the network activity (ping, file transfer, etc.).

Stop capture and analyze packets.

📖 Output Samples
Each experiment includes expected outputs such as:

Terminal output (Java)

HTML responses

Traceroute paths

NS2 visual simulations

CRC remainders

Routing matrices

👨‍💻 Author
Name: Sameer Yaseen

Reg. No.: 2117230020186

📜 License
This project is for educational purposes only.
