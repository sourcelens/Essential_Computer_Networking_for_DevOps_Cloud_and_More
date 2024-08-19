---  
---  


1 : Which layer in the communication stack understands and manages the "syn" packet?  

a) Afd  
b) Ndis  
c) Tcpip  
d) Server program  

**Answer** c)  

**Description**  

Tcpip understands and manages the "syn" packet, which is part of the TCP protocol for establishing connections between peers in a network communication setup.  

---  
---  


2 : Which driver does the "connect" call made by user-mode applications reach first in Windows OS?  

a) TCP/IP  
b) NDIS  
c) AFD  
d) None of the above  

**Answer** c)  

**Description**  

The "connect" call from a user-mode application first reaches the Ancillary Function Driver (AFD), which is responsible for handling network socket operations before interacting with the TCP/IP stack.  

---  
---  


3 : In the context of network communication, what is the typical flow of data between AFD, TCP/IP, and NDIS? (from upper to lower layer) ?  

a) AFD → NDIS → TCP/IP  
b) TCP/IP → AFD → NDIS  
c) AFD → TCP/IP → NDIS  
d) NDIS → TCP/IP → AFD  

**Answer** c)  

**Description**  

In a typical network communication flow, the Ancillary Function Driver (AFD) first receives the data from user-mode applications. This data is then passed to the TCP/IP stack for handling the network protocols (such as TCP and IP). Finally, the data is handed off to the NDIS driver, which interacts with the network interface card (NIC) to transmit the data over the physical network.  

---  
---  







