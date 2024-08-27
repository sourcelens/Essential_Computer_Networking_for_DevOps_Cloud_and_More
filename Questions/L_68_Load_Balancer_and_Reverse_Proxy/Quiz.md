---  
---   


1 : _______ is /are example/s of Load balancer or Reverse proxy.  

a) nginx  
b) haproxy  
c) Apache  
d) All the above  

**Answer** d)  

**Description**  

All are examples of Load balancer or Reverse proxy. nginx is a widely-used open-source web server and reverse proxy server. HAProxy is a free, open-source software that provides high availability load balancing and proxying. Apache, is the most widely used web server software. While primarily a web server, Apache can also function as a reverse proxy.  

---  
---  


2 : Having a server in the front and distribute traffic to different backend servers is _______.  

a) Load Balancing  
b) It is Virtual Private Network  
c) It is Virtual Private Cloud  
d) None of the above  

**Answer** a)  

**Description**  

A load balancer is a server that sits in front of one or more web servers and distributes traffic among them.  

---  
---  


3 : What is a common function of load balancer?  

a) Serves as a DHCP server  
b) Distributing incoming network traffic  
c) Serves as a database for back-end servers  
d) None of the above  

**Answer** b)  

**Description**  

Load balancers distribute incoming network traffic to various backend servers to ensure no single server is overwhelmed.  

---  
---  


4 : How does a load balancer typically determine which server to forward a request when using the round-robin algorithm?  

a) By checking the server with the most available memory  
b) By selecting servers in a sequential order  
c) By choosing servers with the least amount of traffic  
d) None of the above  

**Answer** b)  

**Description**  

In the round-robin algorithm, the load balancer forwards each new request to the next server in a predetermined, sequential order.  

---  
---  


5 : What functionalities can a reverse proxy typically perform?  

a) Authorization and Security  
b) Caching  
c) SSL/TLS termination  
d) All of the above  

**Answer** d)  

**Description**  

All the statements are correct. Reverse proxy enhances security by filter incoming requests, authentication for users, etc. Content Caching: Reverse proxies can cache frequently accessed content, reducing latency and improving response times for clients. SSL Offloading: They can handle SSL/TLS encryption and decryption, reducing the computational load on backend servers.  

---  
---  


6 : A client have no visibility of backend servers in a load-balanced architecture. Is this statement true or false?  

a) True  
b) False  

**Answer** a)  

**Description**  

The client only interacts with the load balancer, and the details of the backend servers are abstracted away, providing no direct visibility of the backend infrastructure to the client.  

---  
---  


7 : What is the purpose of modifying the index.html file on each backend server in the demo setup?  

a) To install Nginx on the backend servers  
b) To identify which backend server is serving the traffic  
c) To change the port number for the load balancer  
d) All the above  

**Answer** b)  

**Description**  

Modifying the index.html file on each backend server allows the user to identify which backend server is serving the traffic by displaying different messages for each server.  

---  
---  


8 : Who acts as the load balancer in the demo setup of the previous lecture?  

a) Apache  
b) Nginx  
c) HAProxy  
d) Tomcat  

**Answer** b)  

**Description**  

In the demo setup, Nginx is used as the load balancer to distribute incoming requests between two backend servers.  

---  
---  






