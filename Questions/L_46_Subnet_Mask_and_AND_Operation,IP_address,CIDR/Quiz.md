---  
---  


1 : In the context of subnet masking, which bitwise operation is commonly used to derive the network address from an IP address and subnet mask?  

a) OR operation  
b) XOR operation  
c) AND operation  
d) NOT operation  

**Answer** c)  

**Description**  

Subnet masking typically involves an AND operation between the IP address and the subnet mask to determine the network address.  

---  
---  


2 : If an IP address is 192.168.1.213 and the subnet mask is 255.255.255.0, what is the network address?  

a) 192.168.1.1  
b) 192.168.1.255  
c) 192.168.1.0  
d) 192.168.1.213  

**Answer** c)  

**Description**  

Performing an AND operation between the IP address 192.168.1.213 and the subnet mask 255.255.255.0 results in the network address 192.168.1.0.  

---  
---  


3 : Which IP address is typically assigned as the default gateway in a subnet?  

a) The first IP address in the subnet  
b) The last IP address in the subnet  
c) Any one of the above  
d) The second IP address in the subnet  

**Answer** d)  

**Description**  

Typically, the default gateway is assigned the second IP address in the subnet (e.g., 192.168.1.1 in a subnet starting at 192.168.1.0). However, technically, any IP address within the subnet can be assigned as the default gateway.  

---  
---  


4 : What does the notation 192.168.1.0/24 represent?  

a) IPv4 network address 192.168.1.0 with a subnet mask of 255.255.255.0  
b) A single host with the IP address 192.168.1.0 and a subnet mask of 255.255.255.255.  
c) A network with a subnet mask of 255.255.0.0, which allows for a larger range of IP addresses  
d) None of the above  

**Answer** a)  

**Description**  

 "192.168.1.0/24" represents the IPv4 network address 192.168.1.0 with a subnet mask of 255.255.255.0, indicating a network where the first three octets (24 bits) are used to identify the network, and the last octet (8 bits) is used for addressing hosts within that subnet.  

 ---  
 ---  


5 : What is the broadcast address for the subnet 192.168.1.0/24?  

a) 192.168.1.0  
b) 192.168.1.1  
c) 192.168.1.255  
d) 192.168.1.254  

**Answer** c)  

**Description**  

The broadcast address for a subnet is the last address in the range. For the subnet 192.168.1.0/24, the broadcast address is 192.168.1.255.  

---  
---  


 6 : In the context of subnetting, what does CIDR stand for?  

 a) Classless Inter-Domain Routing  
 b) Classful Inter-Domain Routing  
 c) Common Inter-Domain Routing  
 d) Complex Inter-Domain Routing  

 **Answer** a)  

**Description**  

CIDR stands for Classless Inter-Domain Routing.  

---  
---  


7 : How many total IP addresses are available in a subnet with a /28 prefix?  

a) 16  
b) 32  
c) 14  
d) 30  

**Answer** a)  

**Description**  

A /28 subnet has 4 bits for host addresses (32 - 28 = 4), 4 trailing zeros, allowing for 2^4 = 16 total IP addresses. Three of these addresses are reserved for the network, broadcast and default gateway addresses, leaving 13 usable addresses for hosts.  

---  
---  


8 : What is the purpose of the broadcast address in a subnet?  

a) To identify the default gateway  
b) To communicate with a specific host  
c) To send a message to all hosts in the subnet  
d) To identify the network address  

**Answer** c)  

**Description**  

The purpose of the broadcast address in a subnet is to allow a message to be sent to all devices within that subnet. This address is used to communicate with all hosts in the network simultaneously.  

---  
---  


9 : What determines if a packet's destination IP address is within the same subnet as the sender?  

a) The subnet mask of the sender  
b) The default gateway of the sender  
c) The MAC address of the sender  
d) None of the above  

**Answer** a)  

**Description**  

The subnet mask of the sender is used to determine if a packet's destination IP address is within the same subnet. This is done by performing an AND operation with the subnet mask and comparing the network portions of the sender's and destination's IP addresses.  

---  
---  


10 : How many total IP addresses are available in a subnet with a /27 prefix?  

a) 16  
b) 32  
c) 14  
d) 30  

**Answer** b)  

**Description**  

A /27 subnet has 5 bits for host addresses (32 - 27 = 5), 5 trailing zeros, allowing for 2^5 = 32 total IP addresses. Three of these addresses are reserved for the network, broadcast and default gateway addresses, leaving 29 usable addresses for hosts.  

---  
---  


11 : Which statement is true about the default gateway in networking?  

a) It is only necessary in large enterprise networks  
b) It is used by devices to communicate outside their subnet  
c) It is typically assigned to the broadcast address  
d) None of the above  

**Answer** b)  

**Description**  

Default gateway allows devices to send packets to destinations outside their own subnet. It acts as a gateway or intermediary that knows how to forward packets between different networks or subnets.  

---  
---  


12 : Who verifies whether the destination IP address is in the same subnet as the source IP address using the subnet mask in the Windows OS?  

a) tcpip.sys  
b) afd.sys  
c) ndis  
d) None of the above  

**Answer** a)  

**Description**  

tcpip.sys verifies whether the destination IP address is in the same subnet as the source IP address using the subnet mask and AND operation.  

---  
---  


13 : What is the result of the AND operation between the IP address 192.168.1.213 and the subnet mask 255.255.255.0?  

a) 192.168.1.255  
b) 192.168.1.213  
c) 192.168.1.0  
d) 192.168.1.1  

**Answer** c)  

**Description**  

The AND operation between the IP address and the subnet mask results in the network address of that subnet, which is 192.168.1.0 in this case.  

---  
---  













