---  
---  


1 : What information does a device use to determine if another device is on the same subnet?  

a) The device compares MAC addresses  
b) The device checks the destination IP address against its own subnet mask 
  
c) The device checks if the destination MAC address matches its default gateway  
d) None of the above  

**Answer** c)  

**Description**  

To determine if a destination device is on the same subnet, the device checks the destination IP address against its own subnet mask and IP address.  

---  
---  


2 : Which of the following best describes the process of sending a packet from a device in one subnet to a device in another subnet?  

a) The packet is sent directly to the destination device using its MAC address  
b) The packet is sent to the source device's router's MAC address  
c) The packet is broadcasted to all devices in both subnets  
d) The packet is sent to the source device's MAC address first  

**Answer** c)  

**Description**  

The packet is sent to the source device's router's MAC address if it is from a device in one subnet to a device in another subnet.  

---  
---  


3 : Which of the following is true when a device sends a packet to another device on the same subnet?  

a) The destination MAC address is the MAC address of the router  
b) The source and destination MAC addresses are both set to the router's MAC address  
c) The destination MAC address is the MAC address of the destination device  
d) The source MAC address is not used  

**Answer** c)  

**Description**  

On the same subnet, devices can communicate directly. The source device uses the destination device's MAC address as the destination MAC address in the frame.  

---  
---  


4 : When devices are on different networks, which MAC address is used for communication?  

a) The MAC address of the destination device  
b) The MAC address of the internet  
c) The MAC address of the router  
d) The MAC address is not used at all  

**Answer** c)  

**Description**  

When devices are on different networks, the device sends the packet to its router's MAC address.  

---  
---  


5 : What determines whether two devices use their own MAC addresses for direct communication?  

a) The devices must be on the same subnet  
b) The devices must have the same IP address  
c) The devices must have the same MAC address  
d) The devices must be connected to different routers  

**Answer** a)  

**Description**  

Devices on the same subnet can communicate directly using their MAC addresses.  

---  
---  

6 : What makes a subnet mask valid?  

a) Having a 32 bit sequence starting with 0's and followed by 1's  
b) Having a 32 bit number with a mixture of 1's and 0's and ending with 1  
c) Having a 32 bit sequence starting with 1's and followed by 0's  
d) None of the above  

**Answer** c)  

**Description**  

A valid subnet mask must have a contiguous sequence of 1's followed by a contiguous sequence of 0's.  

---  
---  


7 : Which of the following binary representations is a valid subnet mask?  

a) 11111111.11111111.11110000.00001111  
b) 11111111.11111111.11111111.00000000  
c) 11111111.11111111.11100000.11100000  
d) 11111111.11111111.00001111.11111111  

**Answer** b)  

**Description**  

The valid subnet mask 11111111.11111111.11111111.00000000 follows the rule of having a contiguous sequence of 1's followed by a contiguous sequence of 0's.  

---  
---  


8 : Which of the following subnet masks is invalid?  

a) 255.255.240.0  
b) 255.255.0.255  
c) 255.255.255.0  
d) 255.255.252.0  

**Answer** b)  

**Description**  

Subnet mask 255.255.0.255 is invalid because it has 0's followed by 1's, which breaks the rule that 0's cannot be followed by 1's in a valid subnet mask.  

---  
---  
