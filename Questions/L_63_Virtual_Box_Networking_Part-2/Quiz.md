---  
---  


1 : In which network mode two VMs running in virtual box can have exactly same IP address?  

a) NAT  
b) Host only  
c) bridged  
d) None of the above  

**Answer** a)  

**Description**  

Two different VMs can have the same IP addresses in two different networks. Because both are two distinct 2^32 address spaces. VMs are isolated from each other and they are also not on the same adapter.  

---  
---  


2 : Ping is a _______ protocol which doesn’t use any port.  

a) Layer 2  
b) Layer 3  
c) Layer 4  
d) None of the above  

**Answer** b)  

**Description**  

Ping is a protocol called ICMP. It is a Layer 3 protocol. It sends some data and checks whether IP address is reachable.  

---  
---  


3 : In NAT network configuration the two VMs Alice and Bob connected to same NAT network can’t have same IP address because _______.  

a) They are on different network  
b) They are on same network  
c) Any of the above  
d) None of the above  

**Answer** b)  

**Description**  

In NAT network configuration if the two VMs Alice and Bob are in same network they can't have same IP address.  

---  
---  


4 : In NAT network configuration can the two VMs Alice and Bob ping each other if they are connected to same NAT network?  

a) Yes  
b) No  

**Answer** a)  

**Description**  

They can ping each other since they are connected to same NAT network. Once they are in seperate NAT network they cant ping each other.  

---  
---  


5 : What does the concept of "bridge networking" in VirtualBox imply?  

a) All VMs share the same IP address  
b) VMs are connected to an external network and get IP addresses from the same DHCP server as the host machine  
c) VMs cannot communicate with each other  
d) VMs are isolated from the host machine's network  

**Answer** b)  

**Description**  

In bridge networking, VMs are connected to the external network and act as if they are directly connected to the same network as the host machine, receiving IP addresses from the same DHCP server.  

---  
---  


6 : In NAT network configuration of VirtualBox VM, which is/are correct?  

a) Have a Virtual router  
b) Two VMs connected to the same NAT network can communicate with each other  
c) Both of the above  
d) None of the above  

**Answer** c)  

**Description**  

In the NAT network configuration of VirtualBox:  There is a virtual router that provides network address translation, allowing the VMs to access external networks.  VMs connected to the same NAT network can communicate with each other and exchange packets.  

---  
---  







