---  
---  

1 : What is the primary purpose of DNS?  

a) To convert IP addresses to domain names  
b) To route packets to the correct destination  
c) To convert domain names to IP addresses  
d) To establish a secure connection between computers  

**Answer** c)  

**Description**  

The primary purpose of DNS (Domain Name System) is to convert human-readable domain names (e.g., google.com) into IP addresses (e.g., 172.217.1.167). This translation is essential for locating and accessing resources on the internet.  

---  
---  


2 : What command in Windows can be used to clear the DNS cache?  

a) ipconfig /all  
b) ipconfig /flushdns  
c) ipconfig /displaydns  
d) nslookup  

**Answer** b)  

**Description**  

ipconfig /flushdns is used to flush (clear) the DNS cache.  

---  
---  


3 : What information does the TTL (Time To Live) field in a DNS response indicate?  

a) How long a DNS cache can serve a DNS record  
b) The time it takes for a packet to reach its destination  
c) The maximum number of hops a packet can take  
d) The time the DNS server took to respond  

**Answer** a)  

**Description**  

TTL (Time To Live) in a DNS response indicates how long the DNS resolver should cache the IP address before querying the DNS server again for the same domain name.  

---  
---  


4 : What happens when the TTL (Time to Live) of a DNS record expires?  

a) A new record is created using the information of old record  
b) The DNS record is refreshed automatically  
c) The DNS record is removed from the cache and needs to be resolved again  
d) The DNS record is backed up  

**Answer** c)  

**Description**  

When the TTL of a DNS record expires, the record is removed from the DNS cache and the domain name needs to be resolved again to obtain a fresh IP address.  

---  
---  


5 : Which protocol does DNS primarily use for queries?  

a) HTTP  
b) FTP  
c) UDP  
d) ICMP  

**Answer** c)  

**Description**  

DNS primarily uses the UDP protocol for queries due to its low overhead and quick transmission. However, DNS can also use TCP for larger queries.  

---  
---  


6 : What is the nslookup command used for?  

a) To trace the route to a destination  
b) To resolve domain names to IP addresses  
c) To configure network interfaces  
d) To encrypt DNS queries  

**Answer** b)  

**Description**  

nslookup (from name server lookup) is a network administration command-line tool for querying the Domain Name System (DNS) to obtain the mapping between domain name and IP address, or other DNS records.  

---  
---  


7 : What happens if a DNS server cannot resolve a domain name?  

a) It denies the request  
b) It refers the request to another DNS server  
c) It automatically assigns an IP address  
d) It redirects the user to a default page  

**Answer** b)  

**Description**  

If a DNS server cannot resolve a domain name, it typically refers the request to another DNS server, often using a hierarchy of servers until the domain is resolved.  

---  
---  


8 : Which of the following best describes a DNS cache?  

a) A storage of web pages  
b) A temporary storage of DNS query results  
c) A list of blocked websites  
d) A repository for email messages  

**Answer** b)  

**Description**  

A DNS cache temporarily stores the results of DNS queries to improve the efficiency of subsequent lookups.  

---  
---  


9 : What does the command nslookup google.com 8.8.8.8 do?  

a) It changes the IP address of google.com to 8.8.8.8  
b) It queries the DNS server at 8.8.8.8 for the IP address of google.com  
c) It sets the local DNS server to 8.8.8.8  
d) None of the above  

**Answer** b)  

**Description**  

The command nslookup google.com 8.8.8.8 queries the DNS server at IP address 8.8.8.8 (which is a public DNS server provided by Google) for the IP address associated with the domain google.com. This command specifies a particular DNS server to use for the query instead of the default DNS server configured on the local machine.  

---  
---  


10 : Which command is used to display all DNS cache entries on a Windows system?  

a) ipconfig /flushdns  
b) nslookup /displaydns  
c) ipconfig /displaydns  
d) netstat /displaydns  

**Answer** c)  

**Description**  

The command ipconfig /displaydns is used to display all DNS cache entries on a Windows system. This command lists all the domain names and their associated IP addresses that have been cached by the DNS client service on the local machine.  

---  
---  


11 : What is the primary function of the DNS client service on a Windows machine?  

a) To act as a DNS server for the network  
b) To manage and maintain the local DNS cache  
c) To automatically update DNS records on the DNS server  
d) To monitor and analyze network traffic  

**Answer** b)  

**Description**  

The DNS Client service is used to resolve DNS domain names, by querying locally cached information obtained from a previous query or by querying a remote DNS server.  

---  
---  


12 : How does a system typically obtain DNS server information?  

a) From the DHCP (Dynamic Host Configuration Protocol) server  
b) By querying the default gateway  
c) Through a pre-configured list in the operating system  
d) None of the above  

**Answer** a)  

**Description**  

A system typically obtains DNS server information automatically from the DHCP server when it connects to a network. The DHCP server provides the necessary network configuration details, including the IP address, subnet mask, gateway, and DNS server addresses.  

---  
---  



