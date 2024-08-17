---  
---  


1 : What is the purpose of adding a close() function to both the client and server sockets in the Python code?  

a) To gracefully terminate the connection between client and server  
b) To forcefully terminate the connection between client and server  
c) For authentication  
d) All of the above  

**Answer** a)  

**Description**  

Adding a close() method to both the client and server sockets allows for the graceful termination of the connection, ensuring proper closure of resources and signaling the end of communication.  

---  
---  


2 : We have the below program,  

```
import socket 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.bind(("127.0.0.1", 65432)) 
s.listen() 
conn, addr = s.accept() 
print(f"Connected by {addr}") 
data = conn.recv(1024)          
conn.sendall(data + b" from server") 
conn.close() 
print("going to end here")
```

Which line of code in the Python server script is responsible for sending the FIN packet?  

a) Line 7  
b) Line 9  
c) Line 10  
d) Line 5  

**Answer** b)  

**Description**  

Line 9 in the server script calls the close() function on the server socket, which sends the FIN packet for the graceful termination of the connection.  

---  
---  


3 : What happens when the close function is called on a socket in a TCP connection?  

a) The socket is immediately terminated without notification  
b) A FIN packet is sent to the other party to initiate connection termination  
c) The socket waits indefinitely for an acknowledgment  
d) The data in the buffer is discarded  

**Answer** b)  

**Description**  

When the close function is called, a FIN packet is sent to the other party to indicate that the sender has finished sending data and wishes to terminate the connection gracefully.  

---  
---  


4 : How do we differentiate packets in Wireshark when both client and server are running on the same physical machine (e.g., using the loopback address 127.0.0.1) ?  

a) By different MAC addresses  
b) By different port numbers  
c) By different encryption keys  
d) By different subnet masks  

**Answer** b)  

**Description**  

Packets from client and server are differentiated using port numbers, especially when the IP addresses are the same.  

---  
---  







