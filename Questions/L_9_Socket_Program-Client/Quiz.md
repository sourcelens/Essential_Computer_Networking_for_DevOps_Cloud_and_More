---  
---  

1 : We have the below program,  

```
import socket 
 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.connect(("127.0.0.1", 65432)) 
s.sendall(b"Hello, world") 
data = s.recv(1024) 
s.close() 
print(f"Received {data!r}")
```

What does Line 3 s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) in the above tcp client socket code do?  

a) Binds the socket to a specific IP address and port number  
b) Creates a new socket object  
c) Listens for incoming connections  
d) None of the above  


**Answer** b)  


**Description**  

This line creates a new socket object  s.  

---  
---  


2 : We have the below program,  

```
import socket 
 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.connect(("127.0.0.1", 65432)) 
s.sendall(b"Hello, world") 
data = s.recv(1024) 
s.close() 
print(f"Received {data!r}")
```

In the above snippet of code, what does Line 4 s.connect(("127.0.0.1", 65432)) do?  

a) Creates new socket object  
b) Receives data from a server  
c) Connects the socket to a server at the specified IP address and port number  
d) Closes the connection  


**Answer** c)  


**Description**  

This line uses the connect function to connect the socket s to a server running on 127.0.0.1 (localhost) at port 65432.  

---  
---  


3 : We have the below program,  

```
import socket 
 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.connect(("127.0.0.1", 65432)) 
s.sendall(b"Hello, world") 
data = s.recv(1024) 
s.close() 
print(f"Received {data!r}")
```

In the above tcp client socket code, what does line 5 s.sendall(b"Hello, world") do?  

a) Creates a new socket object  
b) Receives data from a server  
c) Sends the bytes string b"Hello, world" to the connected server  
d) Closes the connection  


**Answer** c)  


**Description**  

Sends the bytes string b"Hello, world" to the connected server.  This line uses the sendall function to send the byte string b"Hello, world" to the server to which the socket s is connected.  

---  
---  


4 : We have the below program,  

```
import socket 
 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.connect(("127.0.0.1", 65432)) 
s.sendall(b"Hello, world") 
data = s.recv(1024) 
s.close() 
print(f"Received {data!r}")
```

In the python code above, what does line 6 data = s.recv(1024) do?  

a) Sends data to a server  
b) Receives data from the server  
c) Connects the socket to a specific IP address and port number  
d) None of the above  


**Answer** b)  


**Description**  

This line uses the recv function to receive data from the server and stores the received data in the variable data.  

---  
---  


5 : We have the below program,  

```
import socket 
 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.connect(("127.0.0.1", 65432)) 
s.sendall(b"Hello, world") 
data = s.recv(1024) 
s.close() 
print(f"Received {data!r}")
```

In the above client socket code, what does Line 7 s.close() do?  

a) Creates a new socket object  
b) Binds the socket to a specific IP address and port number  
c) Closes the socket s  
d) None of the above  

**Answer** c)  


**Description**

This line uses the close function to close the socket s.  

---  
---  


6 : We have the below program,  

```
import socket 
 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.connect(("127.0.0.1", 65432)) 
s.sendall(b"Hello, world") 
data = s.recv(1024) 
s.close() 
print(f"Received {data!r}")
```

In the above python code, what does line 8 print(f"Received {data!r}") do?  

a) Creates a new socket object  
b) Prints the data received from the server  
c) Connects to a remote server  
d) Puts the socket into listening mode  


**Answer** b)  


**Description**  

This line prints the data received from the server, using f-string formatting to include the received data in a readable format with !r showing the repr() representation of the data.  

---  
---  




