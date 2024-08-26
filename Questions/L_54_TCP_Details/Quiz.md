---  
---  


1 : What is the main purpose of the TCP three-way handshake?  

a) To establish a connection between client and server by setting initial sequence numbers  
b) To encrypt the communication between client and server  
c) To terminate the connection between client and server  
d) None of the above  

**Answer** a)  

**Description**  

The TCP three-way handshake is used to establish a connection by exchanging initial sequence numbers and acknowledging the receipt of these numbers.  

---  
---  


2 : Which two numbers are crucial for the TCP connection between a client and a server?  

a) SYN number  
b) Sequence number and acknowledgment number  
c) Source address and destination address  
d) Window size and congestion control number  

**Answer** b)  

**Description**  

The sequence number and acknowledgment number are crucial for maintaining the TCP connection between a client and a server. These numbers keep track of the amount of data sent and received, ensuring that packets are correctly received and acknowledged.  

---  
---  


3 : Why is TCP considered as a connection-oriented protocol?  

a) It uses IP addresses to establish connections  
b) It maintains state information using sequence and acknowledgment numbers  
c) It encrypts all data sent over the network  
d) It requires a direct physical connection between client and server  

**Answer** b)  

**Description**  

TCP is considered a connection-oriented protocol because it maintains state information using sequence and acknowledgment numbers, which keep track of the data being sent and received. This allows for reliable communication between the client and server.  

---  
---  


4 : Which of the following statements about UDP is true in comparison to TCP?  

a) UDP is connection-oriented like TCP  
b) UDP does not provide reliability, ordering, or data integrity  
c) UDP requires a three-way handshake to establish a connection  
d) UDP uses sequence numbers and acknowledgment numbers  

**Answer** b)  

**Description**  

Unlike TCP, UDP (User Datagram Protocol) does not provide reliability, ordering, or data integrity. It is a connectionless protocol that sends packets without establishing a connection or ensuring that packets are received in order or without errors.  

---  
---  


5 : In the TCP protocol, what does the sequence number represent?  

a) The number of frames received from the other endpoint  
b) The total number of bytes sent from one endpoint to another  
c) A random number used only during the initial handshake  
d) None of the above  

**Answer** b)  

**Description**  

Correct. The sequence number is a counter used to keep track of every byte sent outward by a host.  

---  
---  


6 : How does TCP handle a packet loss in a TCP connection?  

a) It ignores the lost packet and continues sending the next packets  
b) It switches to UDP to resend the lost packet  
c) It terminates the connection immediately upon detecting a lost packet  
d) It sends the packet again using retransmission  

**Answer** d)  

**Description**  

TCP connections can detect lost packets and it sends the packet again using retransmission queue.  

---  
---  


7 : How does the server acknowledge the receipt of data from the client in TCP communication?  

a) By sending a duplicate SYN packet  
b) By sending an acknowledgment (ACK) packet with an incremented acknowledgment number  
c) By resetting the sequence number to zero  
d) By terminating the connection with a FIN packet  

**Answer** b)  

**Description**  

The server acknowledges the receipt of data from the client by sending an acknowledgment (ACK) packet with an incremented acknowledgment number. This increment reflects the amount of data received from the client.  

---  
---  



