NETWORKING

Command Name : ip
Purpose : Display network interfaces and IP addresses.
Syntax : ip addr
Example : ip a
Sample Output : inet 192.168.1.10/24
Explanation : Shows network interfaces and their assigned IP addresses.

⸻

Command Name : ping
Purpose : Test connectivity to another host.
Syntax : ping hostname
Example : ping google.com
Sample Output : 64 bytes from … time=20 ms
Explanation : Checks whether another device or server can be reached over the network.

⸻

Command Name : hostname
Purpose : Display the system hostname.
Syntax : hostname
Example : hostname
Sample Output : paramesh-QEMU-Virtual-Machine
Explanation : Shows the name assigned to the Linux machine.

⸻

Command Name : curl
Purpose : Send requests to websites, servers or APIs.
Syntax : curl URL
Example : curl https://example.com
Sample Output : HTML content from the website.
Explanation : Commonly used to test web servers and APIs from the terminal.

⸻

Command Name : wget
Purpose : Download files from a URL.
Syntax : wget URL
Example : wget https://example.com/file.zip
Sample Output : Saving to: ‘file.zip’
Explanation : Downloads files from web servers to the local machine.

⸻

Command Name : ss
Purpose : Display network connections and listening ports.
Syntax : ss [options]
Example : ss -tuln
Sample Output : Netid State Local Address:Port
Explanation : Helps identify which ports and network services are currently listening.

⸻

Command Name : netstat
Purpose : Display network connections and listening ports.
Syntax : netstat [options]
Example : netstat -tuln
Sample Output : Proto Local Address State
Explanation : Older networking utility used to inspect network connections and ports.

⸻

Command Name : nslookup
Purpose : Find DNS information for a domain.
Syntax : nslookup domain
Example : nslookup google.com
Sample Output : Name: google.com Address: x.x.x.x
Explanation : Shows the IP address associated with a domain name.

⸻

Command Name : dig
Purpose : Query detailed DNS information.
Syntax : dig domain
Example : dig google.com
Sample Output : ANSWER SECTION containing DNS records.
Explanation : Provides detailed information about DNS records and name resolution.

⸻

Command Name : traceroute
Purpose : Display the network path to a destination.
Syntax : traceroute hostname
Example : traceroute google.com
Sample Output : A sequence of network hops.
Explanation : Helps identify the routers or network hops packets travel through before reaching a destination.
