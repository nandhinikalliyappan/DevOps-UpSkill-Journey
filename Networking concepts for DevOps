1. **IP Addressing & Subnetting:**

   - **IP Addressing:** Every device on a network needs a unique address, and understanding how IPs work is fundamental.
   - **IPv4:** This is still the most common IP standard (32-bit), written in the form xxx.xxx.xxx.xxx (e.g., 192.168.1.1).
   - **IPv6:** The newer format with more address space (128-bit).
   - **Private vs. Public IPs:**
     - Private IPs are used within internal networks (like 192.168.x.x).
     - Public IPs are used for internet-facing devices.
   - **Static vs. Dynamic IPs:**
     - Static IPs are fixed.
     - Dynamic IPs are assigned by a DHCP server and can change.
   - **Subnetting:** This involves splitting a larger network into smaller, more manageable sub-networks (subnets). Each subnet has its own IP range, helping to organize and secure traffic.
   - **CIDR Notation (e.g., 192.168.1.0/24):** Specifies the network and the size of the subnet. This allows for more flexible subnetting compared to the old class-based method.

2. **DNS (Domain Name System):**

   - **DNS:** Translates human-friendly domain names (like www.example.com) into IP addresses that computers use to identify each other.
   - **DNS Records:**
     - **A Records:** Maps a domain to an IP address.
     - **CNAME Records:** Aliases for other domains.
     - **MX Records:** Used for mail servers.
   - **DNS Resolution:** The process by which your computer asks a DNS server to resolve a domain name into an IP address.
   - **TTL (Time To Live):** Each DNS record has a TTL value that tells how long the record should be cached before being refreshed.
   - **In DevOps:** You might set up DNS for routing traffic to different environments (e.g., dev.example.com, staging.example.com, prod.example.com) or configure it to route traffic to a load balancer or cloud infrastructure.

3. **Load Balancers:**

   - **Load Balancing:** Distributes incoming network traffic across multiple servers to ensure high availability and reliability. It helps avoid overloading a single server.
   
   - **Types of Load Balancers:**
     - **Layer 4 (TCP/UDP):** Works at the transport layer and forwards traffic based on IP address and port (e.g., AWS ELB Classic Load Balancer).
     - **Layer 7 (HTTP/HTTPS):** Operates at the application layer and can route traffic based on the content (e.g., URL path, HTTP header) (e.g., Nginx, AWS ALB).
   
   - **Benefits:**
     - Load balancing ensures that applications remain responsive, even when the demand spikes or during server maintenance.
     - It’s common to use load balancers in auto-scaling environments to distribute traffic dynamically as new instances are spun up or down.

