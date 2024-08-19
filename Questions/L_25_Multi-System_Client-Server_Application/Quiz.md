---  
---  


1 : Which configuration is used for the network adapter in the virtual machine, running the server in the demo?  

a) NAT  
b) Host-only  
c) Bridged  
d) Internal network  

**Answer** c)  

**Description**  

The network adapter in the virtual machine is configured in bridged mode.  

---  
---  


2 : Which command in Windows displays the IP address of the client laptop?  

a) ipconfig  
b) ifconfig  
c) ping  
d) bridge  

**Answer** b)  

**Description**  

ifconfig is the Linux command.  

---  
---  


3 : In the following tcp socket client program, what does the IP address 172.20.10.6 represent?  

```
import socket 

s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.connect(("172.20.10.6", 65432)) 
s.sendall(b"Hello, world") 
data = s.recv(1024) 
s.close() 
print(f"Received {data!r}")
```

a) IP address of the local host  
b) IP address of the remote host server  
c) Both of the above  
d) None of the above  

**Answer** b)  

**Description**  

The IP address 172.20.10.6 in the s.connect(("172.20.10.6", 65432)) line represents the IP address of the remote host server to which the client program is attempting to establish a connection.  

---  
---  






