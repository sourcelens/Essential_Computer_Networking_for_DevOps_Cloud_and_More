---  
---  


1 : What is the primary purpose of a port number in a TCP layer?  

a) To identify a specific computer on the network  
b) To identify a specific application or process on a computer  
c) To specify the physical location of a server  
d) To determine the size of data packets  

**Answer** c)  

**Description**  

A port number is used to direct network traffic to a specific process or application running on a computer. This allows multiple applications to use the network simultaneously without interfering with each other.  

---  
---  


2 : What is the role of a thread within a process?  

a) To isolate memory between different processes  
b) To manage hardware devices like NIC cards and memory  
c) To run parallel tasks within the same process  
d) To create new processes  

**Answer** c)  

**Description**  

Threads are smaller units of a process that can run in parallel, sharing the same memory space. This allows for efficient execution of tasks that can be done concurrently.  

---  
---  


3 : Why is it important for a listening thread in a server application to spawn worker threads for handling client connections?  

a) To reduce memory usage by using fewer threads  
b) To ensure the server can handle multiple client connections simultaneously  
c) To minimize the number of ports the server uses  
d) None of the above  

**Answer** b)  

**Description**  

By spawning worker threads, the server can handle multiple clients at the same time. The listening thread remains free to accept new connections, while worker threads manage the communication with connected clients.  

---  
---  


4 : What is the advantage of using a thread pool in server applications?  

a) It increases the number of available ports  
b) It reduces the overhead of creating a new thread for each client  
c) It allows direct memory access for each thread  
d) None of the above  

**Answer** b)  

**Description**  

Using a thread pool helps manage resources more efficiently by reusing threads, thereby reducing the overhead associated with creating and destroying threads for each client connection.  

---  
---  


5 : What is true about a single process using multiple ports?  

a) A process can only bind to one port at a time  
b) A process can bind to multiple ports simultaneously using multiple threads  
c) Each port used by a process must be on a different network interface  
d) A process cannot listen on more than one port without causing a conflict  

**Answer** b)  

**Description**  

A single process can bind to multiple ports simultaneously by creating multiple threads, each responsible for listening on a different port. This allows the process to handle various types of traffic or provide different services concurrently.  

---  
---  



