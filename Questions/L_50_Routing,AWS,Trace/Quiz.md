---  
---  


1 : Why do the source and destination IP addresses of the SYN packet match in the client and server Wireshark traces, despite being in different subnets?  

<img src="Images/lecture50_quizpic_25.png" width="500"/>  

a) Because NAT is used between them  
b) Because they are on two different VPC  
c) Because they are on a fully routable network without NAT  
d) Because they use the same MAC addresses  

**Answer** c)  

**Description**  

The client and server IP addresses match in the traces despite being in different subnets because they are communicating over a routable network without Network Address Translation (NAT) involved.  

---  
---  


2 : Why is the destination MAC address in the client and the source MAC address in the server of the SYN packet in Wireshark traces different?  

<img src="Images/lecture50_quizpic_26.png" width="500"/>  

a) The client and server are on the same subnet  
b) The client and server are in different VPC  
c) The client and server are in different subnets, and the packets are routed through default gateways  
d) The server is using Network Address Translation (NAT)  

**Answer** c)  

**Description**  

When packets are routed between subnets, they pass through default gateways, which results in different MAC addresses at each hop.  

---  
---  


3 : Whose MAC address is the destination MAC address in the client trace in the SYN packet?  





