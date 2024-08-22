---  
---  


1 : What is the main function of an ARP request in a subnet?  

a) To find the IP address of a device  
b) To find the MAC address of a device  
c) To find the subnet mask of a network  
d) To find the default gateway of a network  

**Answer** b)  

**Description**  

The main function of an ARP request in a subnet is to resolve (map) an IP address to its corresponding MAC address for devices within the same subnet.  

---  
---  


2 : In a subnet, once the MAC address of the destination is known, how is the packet routed?  

a) Using IP address  
b) Using subnet mask  
c) Using MAC address  
d) None of the above  

**Answer** c)  

**Description**  

Within a subnet, communication happens using MAC addresses after the IP address is used to determine the corresponding MAC address.  

---  
---  


3 : When a client wants to send a packet to an IP address outside its subnet, to which device is the packet first sent?  

a) The final destination device  
b) The subnet mask  
c) The default gateway  
d) Another client in the subnet  

**Answer** c)  

**Description**  

If the destination IP address is outside the client's subnet, the packet is sent to the default gateway, which is typically a router.   

---  
---  


4 : What is a route table in networking?  

a) It is a list of IP addresses assigned to devices in a subnet  
b) It stores routing information, including paths and next-hop IP addresses  
c) It is a table used by DHCP servers to assign IP addresses dynamically  
d) It is a list of DNS servers used for resolving domain names to IP addresses  

**Answer** b)  

**Description**  

A route table in networking is a table stored in a router that contains information about the paths to network destinations. It includes entries that specify which paths or routes are available, what next-hop IP addresses should be used to reach specific networks or hosts etc. Route tables are crucial for routers to make forwarding decisions to determine where to send packets destined for different networks.  

---  
---  


5 : If a router receives a packet with a destination IP address that is not in its subnet, what does it do?  

a) Drops the packet  
b) Uses ARP to find the MAC address  
c) Forwards the packet to another router based on the route table  
d) Sends the packet back to the sender  

**Answer** c)  

**Description**  

The router uses its route table to determine the next destination for the packet and forwards it accordingly.  

---  
---  


6 : When the client realizes the destination IP is outside its subnet, which address does it use in the MAC layer of the packet?  

a) The MAC address of the destination device  
b) The MAC address of the default gateway  
c) The IP address of the destination device  
d) The IP address of the default gateway  

**Answer** b)  

**Description**  

The client uses the MAC address of the default gateway in the MAC layer of the packet when the destination IP is outside its subnet.  

---  
---  








