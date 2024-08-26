---  
---  


1 : What happens if a server does not accept new client requests promptly?  

a) The server's IP address changes  
b) The client may time out and the TCP queue may get flooded  
c) The server automatically terminates  
d) The number of available ports decreases  

**Answer** b)  

**Description**  

If a server does not promptly accept new client requests, the clients may time out, and the TCP queue may get flooded, leading to potential loss of client connections and degraded performance.  

---  
---  


2 : How can a server avoid being overwhelmed by too many client requests at once?  

a) By decreasing the number of available ports  
b) By using a single-threaded model  
c) By creating a new thread for each client connection  
d) By limiting the server's uptime  

**Answer** c)  

**Description**  

To handle multiple client requests without being overwhelmed, the server can create a new thread for each client connection. This allows concurrent processing of multiple requests, improving efficiency.  

---  
---  


3 : What is the potential drawback of creating a new thread for each client request?  

a) It reduces the server's IP address pool  
b) It increases the server's processing time  
c) It can lead to an excessive number of threads and resource exhaustion  
d) It changes the server's port number  

**Answer** c)  

**Description**  

Creating a new thread for each client request can lead to an excessive number of threads, potentially exhausting system resources.  

---  
---  


4 : What concept is recommended for creating efficient servers on Windows operating systems?  

a) Using multiple IP addresses  
b) Implementing IO completion ports  
c) Decreasing port numbers  
d) Adding more delays in the code  

**Answer** b)  

**Description**  

IO completion ports are recommended for creating efficient servers as they manage thread pools effectively and handle IO operations asynchronously.  

---  
---  


5 : What is the key difference between TCP and UDP?  

a) TCP uses port numbers, while UDP does not  
b) TCP does a three-way handshake, while UDP does not  
c) UDP is more reliable than TCP  
d) UDP requires a three-way handshake, while TCP does not  

**Answer** b)  

**Description**  

TCP does a three-way handshake (SYN, SYN-ACK, ACK) to establish a connection, while UDP is connectionless and does not require such a handshake.  

---  
---  

