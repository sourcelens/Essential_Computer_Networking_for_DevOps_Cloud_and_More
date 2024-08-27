---  
---  


1 : Which of the following commands is used in Linux to check the IP configuration of a system, similar to ipconfig in Windows?  

a) ifconfig  
b) iptables  
c) netstat  
d) wget  

**Answer** a)  

**Description**  

The ifconfig command in Linux is used to check the IP configuration of a system, similar to ipconfig in Windows. It displays network interfaces and their corresponding IP addresses.  

---  
---  


2 : Which command in Linux is used to send ICMP echo requests to check network connectivity, similar to ping in Windows?  

a) wget  
b) ping  
c) curl  
d) nc  

**Answer** b)  

**Description**  

The ping command in Linux is used to send ICMP echo requests to check network connectivity, similar to the ping command in Windows.  

---  
---  


3 : Which command in Linux can behave as both a TCP server and a TCP client?  

a) ping  
b) curl  
c) nc (netcat)  
d) ifconfig  

**Answer** c)  

**Description**  

The nc (netcat) command in Linux can behave as both a TCP server and a TCP client, making it a versatile tool for network debugging.  

---  
---  


4 : What is the primary function of the curl command in Linux?  

a) To configure network interfaces  
b) Allows data transfer to or from a server  
c) To manage firewall settings  
d) None of the above  

**Answer** b)  

**Description**  

The curl command in Linux is primarily used to transfer data from or to a server.  

---  
---  


5 : What does the command "curl google.com" does?  

a) Performs an HTTP GET request to the URL google.com  
b) It downloads and saves the HTML content of google.com to a file named google.html  
c) It opens the google.com website in the default web browser  
d) All the above  

**Answer** a)  

**Description**  

The command curl google.com performs an HTTP GET request to the URL google.com.  

---  
---  


6 : What does the command "nc -l 1234" do?  

a) Netcat to listen for incoming connections on port 1234  
b) To connect to a server  
c) To download a file  
d) None of the above  

**Answer** a)  

**Description**  

We’re using the ‘-l’ option (which stands for ‘listen’) to tell Netcat to listen for incoming connections on port 1234.  

---  
---  


7 : Which format of netcat (nc) command is used to connect to a remote host from a Linux machine?  

a) nc -l -p 1234  
b) nc -l 1234  
c) nc <IPaddress> <port>  
d) None of the above  

**Answer** c)  

**Description**  

Correct. The command nc 10.0.2.5 65432 using nc (netcat) attempts to establish a connection to the IP address 10.0.2.5 on port 65432.  

---  
---  


8 : What is the primary function of the telnet command in Linux?  

a) To connect to remote servers using the Telnet protocol  
b) To encrypt network traffic  
c) Both of the above  
d) None of the above  

**Answer** a)  

**Description**  

Telnet is used to connect to remote servers using the Telnet protocol, typically for remote management purposes.  Telnet is not secure and is generally replaced by SSH.  

---  
---  


9 : What does the wget command do in Linux?  

a) It download files from the internet  
b) It compresses and archives files  
c) Both are correct  
d) None of the above  

**Answer** a)  

**Description**  

wget is a command-line utility for downloading files from the internet. Files are automatically saved in your current work folder.  

---  
---  


10 : Which of the following is a key difference between wget and curl?  

a) wget is designed to download files by default, whereas curl does not save files by default  
b) wget is a graphical tool, while curl is command-line based  
c) wget automatically follows redirects whereas curl doesn't and requires explicit use of the -L option to do so  
d) Both a and c  

**Answer** d)  

**Description**  

wget is designed to download files by default. curl -o index.html https://example.com/index.html is the format to download websites/files using curl command.  wget automatically follows redirects, making it convenient for tasks that involve multiple URLs, whereas curl doesn't and requires explicit use of the -L option to do so.  

---  
---  


11 : What does the netstat command in Linux primarily display?  

a) Active connections and listening ports  
b) Disk usage and file statistics  
c) Installed software packages and their versions  
d) None of the above  

**Answer** a)  

**Description**  

`netstat` stands for network statistics. It allows users to display network-related information and diagnose various networking issues. The command has several options that can be combined to retrieve specific details. It can tell you about the connections your computer is making and can list all ports being used.  

---  
---  


12 : What is the primary use of the tcpdump command in Linux?  

a) To monitor disk usage  
b) To capture and analyze network packets  
c) To list running processes  
d) To manage file permissions  

**Answer** b)  

**Description**  

tcpdump is a powerful command-line packet analyzer that is used to capture and analyze network packets in real-time in Linux systems.  

---  
---  


13 : How can you specify the interface on which tcpdump should capture packets?  

a) tcpdump -i <interface>  
b) tcpdump -d <interface>  
c) tcpdump -p <interface>  
d) tcpdump -n <interface>  

**Answer** a)  

**Description**  

The -i option is used with tcpdump to specify the network interface on which to capture packets.  

---  
---  


14 : How can you write the captured packets  from an interface to a file using tcpdump?  

a) tcpdump -i <interface> -s 65535 -w <filename>  
b) tcpdump -i <interface> -s 65535 -r <filename>  
c) tcpdump -i <interface> -s 65535 -f <filename>  
d) None of the above  

**Answer** a)  

**Description**  

The -w option is used with tcpdump to write the captured packets to a file.  

---  
---  


15 : What is the primary purpose of the ip command in Linux?  

a) To manage file permissions  
b) To manage network interfaces  
c) To monitor system performance  
d) To install software packages  

**Answer** b)  

**Description**  

The ip command is primarily used to manage network interfaces and other network settings.  

---  
---  


16 : Which of the following commands displays the current IP addresses of all network interfaces in Linux system?  

a) ip addr  
b) ip link show  
c) ip route show  
d) ip netns show  

**Answer** a)  

**Description**  

ip addr, ip a or ip address command displays the IP addresses assigned to all network interfaces in Linux system.  

---  
---  


17 : How do you add a new IP address to an interface using the ip command in Linux?  

a) ip a add {ip_addr/mask} sin {interface}  
b) ip l add {ip_addr/mask} dev {interface}  
c) ip a add {ip_addr/mask} dev {interface}  
d) None of the above  

**Answer** c)  

**Description**  

ip a add {ip_addr/mask} dev {interface} command is used to add a new IP address to an interface using the ip command in Linux.  For eg: ip a add 192.168.1.200/255.255.255.0 dev eth0.  


18 : How would you display the current routing table using the ip command?  

a) ip route  
b) ip link  
c) ip addr  
d) ip netns   

**Answer** a)  

**Description**  

The ip route command displays the current routing table.  

---  
---  


19 : Which iptables option is used to list all current rules in Linux system?  

a) -A  
b) -D  
c) -L  
d) -F  

**Answer** c)  

**Description**  

The -L option is used with iptables to list all current rules in all chains.  

---  
---  


20 : What is the primary purpose of the iptables command in Linux?  

a) To manage user permissions  
b) To configure firewall rules  
c) To monitor disk usage  
d) None of the above  

**Answer** b)  

**Description**  

The iptables command in Linux is a powerful tool that is used for managing the firewall rules and network traffic. It facilitates allowing the administrators to configure rules that help how packets are filtered, translated, or forwarded.  

---  
---  


21 : How do you save the current iptables rules to a file in Linux?  

a) iptables-save > /path/nameoffile  
b) iptables --backup /path/nameoffile  
c) iptables --store /path/nameoffile  
d) None of the above  


**Answer** a)  

**Description**  

To save the current iptables rules to a file, you use the iptables-save command and redirect the output to a file.  

--- 
---  


22 : What does the netsh interface portproxy add v4tov4 command do in Windows?  

a) Adds a new route to the routing table  
b) Sets up port forwarding from one IPv4 address/port to another IPv4 address/port  
c) Lists all open network connections  
d) None of the above  

**Answer** b)  

**Description**  

The netsh interface portproxy add v4tov4 command in Windows is used to set up port forwarding from one IPv4 address/port to another IPv4 address/port.  

---  
---  


23 : netsh interface portproxy add v4tov4 listenport=1233 listenaddress=0.0.0.0 connectport=65432 connectaddress=127.0.0.1

What is the primary purpose of the above command in Windows?  

a) To create a new network interface  
b) To add a route to the routing table  
c) To set up port forwarding from port 1233 to port 65432  
d) None of the above  

**Answer** c)  

**Description**  

This command sets up port forwarding from port 1233 on the local machine to port 65432 on the same local host.  

---  
---  


24 : What does listenaddress=0.0.0.0 signify in the following netsh command?

netsh interface portproxy add v4tov4 listenport=1233 listenaddress=0.0.0.0 connectport=65432 connectaddress=127.0.0.1  

a) It listens on a specific IP address only  
b) It listens on all available IP addresses  
c) It disables the listening on the specified port  
d) None of the above  

**Answer** b)  

**Description**  

listenaddress=0.0.0.0 means the command will listen on all available IP addresses on the machine.  

---  
---  


25 : What does connectaddress=127.0.0.1 in the below netsh command specify?

netsh interface portproxy add v4tov4 listenport=1233 listenaddress=0.0.0.0 connectport=65432 connectaddress=127.0.0.1  

a) The address to which traffic will be forwarded  
b) The broadcast address  
c) Both of the above  
d) None of the above  


**Answer** a)  

**Description**  

connectaddress in the command is the address to which traffic will be forwarded. connectaddress=127.0.0.1 specifies that the traffic will be forwarded to the localhost.  

---  
---  

