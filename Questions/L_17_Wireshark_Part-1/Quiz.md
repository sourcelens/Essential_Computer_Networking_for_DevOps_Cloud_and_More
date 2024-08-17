---  
---  


1 : What is the main difference between Wireshark and other tools like Process Monitor?  

a) Wireshark captures the actual data going on the network  
b) Wireshark only captures metadata of the packets  
c) Wireshark captures screenshots of application processes  
d) Wireshark only works with TCP/IP protocols  

**Answer** a)  

**Description**  

Unlike tools like Process Monitor which capture metadata, Wireshark captures the actual data being transmitted over the network, allowing for detailed packet analysis.  

---  
---  


2 : What is Wireshark primarily used for?  

a) Editing network configurations  
b) Monitoring application performance  
c) Capturing and analyzing network traffic  
d) Managing database systems  

**Answer** c)  

**Description**  

Wireshark is a network sniffer tool that captures and analyzes the packets sent and received over a network.  

---  
---  


3 : Why might Wireshark not display the process name associated with the captured packets?  

a) Wireshark focuses on lower network layers where process names are not relevant  
b) Process names are not transmitted over the network  
c) Wireshark requires additional plugins to display process names  
d) All of the above  

**Answer** a)  

**Description**  

Wireshark captures data at lower layers of the network stack, where the concept of process names does not exist, as it is concerned with packets and data transmission rather than application-level details.  

---  
---  


4 : Why did we choose a specific network interface card (NIC) i.e “loopback traffic capture” in Wireshark?  

a) To monitor all network traffic on the system  
b) To filter out unwanted network traffic  
c) To capture loopback traffic  
d) Both b and c  

**Answer** d)  

**Description**  

It is the correct answer. To narrow down traffic to local applications. Since our server and client run on the same system we selected “loopback traffic capture”. Filtering helps reduce noise and allows you to concentrate on relevant data. Selecting a specific NIC allows Wireshark to capture traffic specific to that interface, such as loopback traffic, which is often used for local communication between applications on the same machine.  

---  
---  


5 : What is the purpose of the three-way handshake in TCP connections?  

a) To establish a secure encrypted channel  
b) For reliable data transmission  
c) To authenticate the client to the server  
d) To negotiate the maximum transmission unit (MTU) size  


**Answer** b)  

**Description**  

The three-way handshake is a process in TCP connections where the client and server exchange SYN (synchronize) and ACK (acknowledge) packets to establish connection parameters, including sequence numbers, for reliable data transmission.  

---  
---  


6 : What does the “three-way handshake” in a TCP connection involve?  

a) FIN, RST, ACK  
b) SYN, SYN-ACK, ACK  
c) PUSH, ACK, SYN  
d) SYN, FIN, ACK  

**Answer** b)  

**Description**  

The three-way handshake in TCP connections involves SYN, SYN-ACK, and ACK packets, which establish a connection between the client and server.  

---  
---  


7 : In TCP communication, which flag is used to initiate a connection?  

a) SYN  
b) ACK  
c) FIN  
d) PSH  

**Answer** a)  

**Description**  

The SYN (Synchronize) flag is used to initiate a connection establishment process in TCP. The sender initiates a connection by sending a SYN packet. It requests the recipient to synchronize sequence numbers for establishing a connection. Think of it as saying, “Hey, let’s start a conversation!”.  

---  
---  


8 : What does the PSH flag indicate in TCP communication?  

a) The start of a connection  
b) The acknowledgment of received data  
c) The intention to terminate the connection  
d) The request to push data to the receiving application  

**Answer** d)  

**Description**  

The PSH (Push) flag is used in TCP communication to indicate the sender's request to push data to the receiving application immediately, without waiting to buffer it.  

---  
---  


9 : What does an RST-ACK packet indicate when a client attempts to connect to a server?  

a) Successful connection establishment  
b) Graceful termination of a connection  
c) Connection refusal by the server  
d) Data transfer completion  

**Answer** c)  

**Description**  

An RST-ACK packet indicates that the server is refusing the connection, often because there is no application listening on the requested port.  

---  
---  





