---  
---  


1 : What does the ARP protocol stands for?  

a) Address Resolution Protocol  
b) Address Routing Protocol  
c) Automated Routing Protocol  
d) Address Relay Protocol  

**Answer** a)  

**Description**  

ARP stands for Address Resolution Protocol. It is used to map IP addresses to MAC addresses within a local network.  

---  
---  


2 : What is the primary purpose of ARP ?  

a) To assign IP addresses to devices on a network  
b) To map IP addresses to MAC addresses  
c) To encrypt data transmitted over the network  
d) To manage routing tables in routers  

**Answer** b)  

**Description**  

ARP is used to map IP addresses to MAC addresses.  

---  
---  


3 : What command is used in Windows to view the ARP cache?  

a) ipconfig  
b) netstat  
c) arp -a  
d) tracert  

**Answer** c)  

**Description**  

The command arp -a is used in Windows to view the ARP cache, showing the learned MAC addresses for IP addresses in the local network.  

---  
---  


4 : Which of the following best describes a broadcast packet in the context of ARP?  

a) sent to a specific MAC address  
b) sent to a specific IP address  
c) sent to all devices in the subnet  
d) sent to all devices on the internet  

**Answer** c)  

**Description**  

In the context of ARP, a broadcast packet is sent to all devices in the subnet to query for the MAC address associated with a specific IP address.  

---  
---  


5 : What does the ARP cache do?  

a) Stores the IP addresses of all devices in the internet  
b) Stores the MAC addresses of all devices in the network  
c) Temporarily stores recently resolved IP-to-MAC address mappings 
 
 d) Permanently stores IP-to-MAC address mappings  

**Answer** c)  

**Description**  

The ARP cache temporarily stores IP-to-MAC address mappings to avoid repeatedly sending ARP requests for the same IP addresses.  

---  
---  

6 : What command is used to clear the ARP cache on Windows?  

a) arp -d  
b) ipconfig  
c) ipdelete  
d) arp -c  

**Answer** a)  

**Description**  

The command arp -d is used to clear the ARP cache on Windows, forcing the system to send new ARP requests.  

---  
---  


7 : To which MAC address the ARP broadcast packet is send?  

a) 28:EE:52:B8:54:3B  
b) 82:EE:52:B8:54:7A  
c) 00:00:00:00:00:00  
d) ff:ff:ff:ff:ff:ff  

**Answer** a)  

**Description**  

The ARP (Address Resolution Protocol) broadcast packet is sent to the MAC address ff:ff:ff:ff:ff:ff. To ensure all devices within the subnet receive the ARP request, it is sent to the broadcast MAC address.  

---  
---  


8 : What does a device do when it receives an ARP Request?  

a) It assigns a new IP address to itself  
b) It replies with an ARP Reply containing its MAC address if it owns the IP address  
c) It broadcasts the request to all devices outside the network  
d) None of the above  

**Answer** b)  

**Description**  

The device replies with an ARP Reply containing its MAC address if it owns the IP address.  

---  
---  


9 : What does an ARP request contain?  

a) Sender's MAC Address, Sender's IP Address  
b) Target's IP Address  
c) Target's MAC Address field set to all zeros as it is unknown and is what the request is attempting to discover.  
d) All of the above  

**Answer** b)  

**Description**  

Sender's MAC Address:The hardware (MAC) address of the device sending the ARP request.Sender's IP Address: The IP address of the device sending the ARP request.Target's IP Address: The IP address for which the MAC address is being requested.Target's MAC Address:This field is set to all zeros in the ARP request, as it is unknown and is what the request is attempting to discover.  

---  
---  
