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


7 : 



