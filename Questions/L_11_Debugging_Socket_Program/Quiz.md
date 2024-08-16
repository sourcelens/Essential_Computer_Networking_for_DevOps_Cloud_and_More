---  
---  

1 : What is the significance of the yellow arrow during debugging in VS Code?  

a) It indicates a successful execution  
b) It points to the line about to be debugged  
c) It marks lines with syntax errors  
d) It represents a pause in execution  

**Answer** b)  

**Description**  

The yellow arrow in VS code during debugging will point to the line to be debugged.  

---  
---  


2 : What does the error message "no connection could be made because the target machine actively refused it" while running the tcp socket client code imply?  

a) The server is unreachable  
b) The client-side code is faulty  
c) The network connection is unstable  
d) The server actively denied the connection  

**Answer** d)  

**Description**  

The error message suggests that the server actively refused the connection attempt made by the client.  

---  
---  


3 : When does the tcp server socket code execute the accept function?  

a) After the client has called connect  
b) Before binding to an IP address and port  
c) After sending data to the client  
d) None of the above  

**Answer** a) 

**Description**  

The accept function on the server side is executed after the client has called connect. accept blocks and waits for an incoming connection request from the client.  

---  
---  


4 : In which order should the following functions be executed in a typical tcp client socket code?

1. connect  
2. recv  
3. sendall  
4. close

a) 1, 3, 2, 4  
b) 1, 2, 3, 4  
c) 3, 1, 2, 4  
d) 4, 3, 2, 1  

**Answer** a)  

**Description**  

In a typical tcp client socket code, the order is:  
connect to the server, sendall to send data to the server, recv to receive data from the server, close to terminate the connection.  

---  
---  


5 : What is the correct sequence of function calls in a tcp server socket code to handle incoming client connections?

1. bind  
2. listen  
3. accept  
4. recv  
5. sendall  
6. close  

a) 1, 2, 3, 4, 5, 6  
b) 2, 1, 3, 4, 5, 6  
c) 3, 1, 2, 4, 5, 6  
d) 1, 3, 2, 4, 5, 6  


**Answer** a)  

**Description**  

In a typical tcp server socket code, the order is :  
1. bind to an IP address and port,  
2. listen to put the socket into listening mode,  
3. accept to wait for and accept incoming connections,  
4. recv to receive data from the client,  
5. sendall to send data to the client,  
6. close to terminate the connection.

---  
---  
   
