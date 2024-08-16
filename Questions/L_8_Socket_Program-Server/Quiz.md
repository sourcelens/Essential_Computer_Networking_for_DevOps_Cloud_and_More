---  
---  

1 : The code inside a tcp socket server application will have ____?  

a) Bind  
b) Listen  
c) Accept  
d) All of the above  


**Answer** d)  


**Description**

When writing server-side applications, particularly for network communication, the code often includes several key functions to handle incoming connections.  Some of these key functions are Bind, Listen and Accept.  

---  
---  


2 : The operation ‘bind’ in networking takes which information/s mainly?  

a) IP address  
b) Port number  
c) Both of the above  
d) None of the above  


**Answer** c)  


**Description**  

Mainly bind operation takes information as two numbers ie, IP address and port number. 

---  
---  


3 : The two functions in tcp socket server code which make the server different from client are____?  

a) Listen  
b) Accept  
c) Both of the above  
d) None of the above  


**Answer** c)  


**Description**  

Listen and Accept are the two functions in server code which make server different from client. Client doesn’t listen and accept. In server we are listening for client connections.  

---  
---  


4 : We have the below program,  

```
import socket 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.bind(("127.0.0.1", 65432)) 
s.listen() 
conn, addr = s.accept() 
print(f"Connected by {addr}") 
data = conn.recv(1024) 
print(f"Received {data!r}")             
conn.sendall(data)
```

The function ‘accept’ in the tcp socket server side code waits for a client connection, and it returns____?  

a) Returns the function name  
b) Returns the address of the connected client  
c) Both of the above  
d) None of the above  


**Answer** b)  


**Description**  

The function ‘accept’ in the tcp socket server side code waits for a client connection, and it returns the address of the connected client (addr).  

---  
---  


5 : We have the below program,  

```
import socket

s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

s.bind(("127.0.0.1", 65432))

s.listen()

conn, addr = s.accept()

print(f"Connected by {addr}")

data = conn.recv(1024)

print(f"Received {data!r}")

conn.sendall(data)
```

What does Line 1[import socket] of the above python code do?  

a) Imports the socket module  
b) Prints a message  
c) Receives data from the client  
d) None of the above  


**Answer** a)  


**Description**  

Line 1 imports the socket module in Python. This module allows Python programs to create and use sockets for network communication.  

---  
---  


6 : We have the below program, 

```
import socket 

s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 

s.bind(("127.0.0.1", 65432)) 

s.listen() 

conn, addr = s.accept() 

print(f"Connected by {addr}") 

data = conn.recv(1024) 

print(f"Received {data!r}")             

conn.sendall(data)
```

What does Line 3 [s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)] of the above python code do?  

a) Imports a module  
b) Connect to client  
c) Creates a new socket object named s  
d) All the above  


**Answer** c)  


**Description**  

Line 3 creates a new socket object named s.  

---  
---  


7 : We have the below program,  

```
import socket 

s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 

s.bind(("127.0.0.1", 65432)) 

s.listen() 

conn, addr = s.accept() 

print(f"Connected by {addr}") 

data = conn.recv(1024) 

print(f"Received {data!r}")             

conn.sendall(data)
```

What does Line 5 s.bind(("127.0.0.1", 65432)) of the above python code do?  

a) Binds the socket s to a specific network interface and port  
b) Blocks until a client connects to the server  
c) Both a and b  
d) None of the above  


**Answer** a)  


**Description**  

Line 5 binds the socket s to a specific network interface and port. In this case, it binds to the IP address 127.0.0.1 (which represents the local machine) and port 65432. This means that the socket will listen for incoming connections on port 65432 of the local machine.  

---  
---  


8 : We have the below program,  

```
import socket 

s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 

s.bind(("127.0.0.1", 65432)) 

s.listen() 

conn, addr = s.accept() 

print(f"Connected by {addr}") 

data = conn.recv(1024) 

print(f"Received {data!r}")             

conn.sendall(data)
```

In the following snippet of tcp socket Server code, what does line 7 s.listen() do?  

a) Puts the socket into listening mode for incoming client connections  
b) Receives data from a client  
c) Sends data to a remote server  
d) None of the above  


**Answer** a)  


**Description**  

Line 7 puts the socket s into listening mode, for incoming connections from clients. Therefore, the correct answer is a).  

---  
---  


9 : We have the below program,  

```
import socket 

s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 

s.bind(("127.0.0.1", 65432)) 

s.listen() 

conn, addr = s.accept() 

print(f"Connected by {addr}") 

data = conn.recv(1024) 

print(f"Received {data!r}")             

conn.sendall(data)
```

In the below snippet of tcp socket Server code, what does line 9 conn, addr = s.accept() do?  

a) Imports socket module  
b) Blocks until a client connects to the server  
c) Accepts an incoming connection from a client and returns the address of the connected client (addr).  
d) Both b and c  


**Answer** d)  


**Description**  

Line 9 blocks until a client connects to the server, when a client connects, then it accepts the incoming connection and returns a new socket object (conn) that represents the connection to the client and addr containing the client's address. Therefore, the correct answer is d).  

---  
---  


10 : We have the below program,  

```
import socket 

s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 

s.bind(("127.0.0.1", 65432)) 

s.listen() 

conn, addr = s.accept() 

print(f"Connected by {addr}") 

data = conn.recv(1024) 

print(f"Received {data!r}")             

conn.sendall(data)
```

In the above snippet of tcp socket Server code, what does line 11 print(f"Connected by {addr}") do?  

a) Accepts an incoming connection from a client and returns conn and client address  
b) Receives data from a client  
c) Prints the client’s address  
d) Binds the socket  


**Answer** c)  


**Description**  

Prints the client’s address. Line 11 prints the client’s address indicating that a connection has been successfully established with a client.  

---  
---  


11 : We have the below program,  

```
import socket 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.bind(("127.0.0.1", 65432)) 
s.listen() 
conn, addr = s.accept() 
print(f"Connected by {addr}") 
data = conn.recv(1024) 
print(f"Received {data!r}")             
conn.sendall(data)
```

In the above snippet of code, what does line 7 data = conn.recv(1024) do?  

a) Receives data from a client  
b) Accepts an incoming connection from a client  
c) Closes an existing connection  
d) None of the above  


**Answer** a)  


**Description**  

Line 7 receives data from the client connected to the socket and stores the received data in the variable data. Therefore, the correct answer is a).  

---  
---  


12 : We have the below program, 

```
import socket 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.bind(("127.0.0.1", 65432)) 
s.listen() 
conn, addr = s.accept() 
print(f"Connected by {addr}") 
data = conn.recv(1024) 
print(f"Received {data!r}")             
conn.sendall(data)
```

In the above snippet of python code what does line 8 print(f"Received {data!r}") do?  

a) Receives data from client  
b) Returns the client address  
c) Blocks until a client connects to the server  
d) Prints the data received from the client  


**Answer** d)  


**Description**  

Line 8 Prints the data received from the client, using f-string formatting to include the received data in the output message. f-string formatting in Python offers a convenient and powerful way to format strings with expressions, enhancing readability and flexibility in your code.  

---
---


13 : We have the below program,  

```
import socket 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM) 
s.bind(("127.0.0.1", 65432)) 
s.listen() 
conn, addr = s.accept() 
print(f"Connected by {addr}") 
data = conn.recv(1024) 
print(f"Received {data!r}")             
conn.sendall(data)
```

In the above tcp socket Server code, what does line 9 conn.sendall(data) do?  

a) Sends data to the client  
b) Receives data from client  
c) Prints the address of client  
d) None of the above  


**Answer** a)  


**Description**  

Line 9 conn.sendall(data) Sends data to client.  

---  
---  




