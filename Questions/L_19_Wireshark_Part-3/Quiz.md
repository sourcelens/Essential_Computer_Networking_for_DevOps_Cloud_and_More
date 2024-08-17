---  
---  


1 : What is the primary difference between graceful and non-graceful termination of a program?  

a) Graceful termination involves cleaning up resources, while non-graceful termination does not  
b) Graceful termination occurs when the program ends abruptly, while non-graceful termination occurs when program ends  
c) Graceful termination requires user input, while non-graceful termination does not  
d) Graceful termination only occurs in debug mode, while non-graceful termination occurs in production  

**Answer** a)  

**Description**  

Graceful termination refers to the process of properly closing resources and cleaning up after a program, such as closing connections, releasing memory, etc. Non-graceful termination, on the other hand, happens abruptly without performing any cleanup tasks.  

---  
---  


2 : How can a non-graceful termination of a TCP connection be achieved in Python?  

a) Using the exit() function  
b) Pressing Ctrl+C in the terminal  
c) Stopping execution in a debugger and non gracefully terminate the application.  
d) All of the above  

**Answer** c)  

**Description**  

Stopping execution in a debugger, such as pressing the stop button or using keyboard shortcuts like Shift+F5, interrupts the program's execution abruptly, resulting in non-graceful termination of a TCP connection.  

---  
---  


3 : What happens when a program terminates non-gracefully?  

a) The program exits cleanly, performing all necessary cleanup tasks  
b) Resources created by the program are not properly released  
c) The program enters debug mode automatically  
d) The program is restarted automatically by the operating system  


**Answer** b)  

**Description**  

Non-graceful termination means the program ends abruptly without performing necessary cleanup tasks, leaving resources allocated by the program potentially unreleased.  

---  
---  


4 : How does the operating system handle non-graceful termination of a TCP socket application?  

a) It sends a graceful termination signal  
b) It sends a reset packet  
c) It prompts the user to confirm termination  
d) It logs the termination event for debugging purposes  

**Answer** b)  

**Description**  

When a TCP socket application terminates non-gracefully, the operating system sends a reset packet to the peer, indicating that the connection has been forcibly closed.  

---  
---  


5 : What role does the operating system play in non-graceful termination of a TCP socket program?  

a) It cleans up only the memory allocated by the program.  
b) It initiates cleanup of program objects, resource as well as the memory allocated by the program.   
c) It notifies the user about the termination event  
d) It prevents non-graceful termination from occurring  

**Answer** b)  

**Description**  

In non-graceful termination, the operating system takes over cleanup responsibilities, closing connections and releasing resources on behalf of the terminated program.  

---  
---  


6 : What happens when a TCP connection is terminated non-gracefully by ending the program using a debugger or task manager?  

a) The connection is terminated with a FIN packet  
b) The connection is terminated with a RST packet  
c) The connection remains open indefinitely  
d) The operating system sends a SYN-ACK packet  

**Answer** b)  

**Description**  

When a program is terminated abruptly (e.g., using a debugger or task manager), the operating system sends a RST packet to indicate an abnormal termination of the connection.  

---  
---  


7 : Who sends the RST packet during a non-graceful termination of a TCP connection?  

a) The application  
b) The Python runtime  
c) The operating system  
d) The network hardware  

**Answer** c)  

**Description**  

During a non-graceful termination, the RST packet is sent by the operating system to inform the peer that the connection has been forcibly closed.  

---  
---  


8 : What is indicated by the error message "an existing connection was forcibly closed by the remote host" in the tcp server socket code?  

a) The connection was closed gracefully  
b) The connection was terminated by the remote host using a FIN packet  
c) The connection was forcibly terminated by the remote host which typically involves sending a RST packet  
d) The connection was re-established by the remote host  


**Answer** c)  

**Description**

The message indicates that the connection was forcibly terminated by the remote host, which typically involves sending a RST packet.  

---  
---  

