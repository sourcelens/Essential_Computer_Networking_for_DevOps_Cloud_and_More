---  
---  

1 : Connect is a call which is coming from _____ in a client-server relation?  

a) Server to client   
b) Client to server  
c) Any of the above  
d) None of the above  

**Answer** b)  

**Description**  

Connect call always comes from a client to the server.  The server is waiting on accept. 

---  
---  


2 : There can be _____ client/s connecting to a web server like google or Facebook which is listening to a particular port?  

a) Only one  
b) Any number  
c) Only two  
d) None of the above  

**Answer** b)  

**Description**  

It can be any number.

---  
---  


3 : The first packet of data in a server-client connection is send by ______ .  

a) Server  
b) Client  
c) Both of the above  
d) None of the above  

**Answer** b)  

**Description**  

In a typical server-client connection, the first packet of data is sent by the client. The server creates a socket and binds it to a specific IP address and port. The server then listens for incoming connection requests. The client creates a socket and connects to the server's IP address and port. The connect() call from the client sends a SYN (synchronize) packet to the server to initiate the TCP handshake (in the case of TCP connections).  

---  
---  


4 : What does the listen function do on the server side in a TCP connection?  

a) It sends data to the client  
b) It binds the socket to a specific IP address and port number  
c) It puts the socket into listening mode  
d) It closes the socket  

**Answer** c)  

**Description**  

The listen function puts the socket into listening mode, allowing it to listen to incoming connections.   

---  
---  


5 : What does the accept function do on the server side in a TCP connection?  

a) Sends data to the client  
b) Blocks execution and waits for an incoming connection  
c) Closes the socket  
d) None of the above  

**Answer** b)  

**Description**  

The accept function is used on the server side to wait for incoming connection requests.   

---  
---  


6 : What does the connect function do on the client side in a TCP connection?  

a) Puts the socket into listening mode  
b) Binds the socket to a specific IP address and port number  
c) It establishes a connection to a remote server specified by its IP address and port number  
d) Closes the socket  

**Answer** c)  

**Description**  

The connect function is used on the client side to establish a connection to a remote server. The client provides the server's IP address and port number to connect to.  

---  
---  

