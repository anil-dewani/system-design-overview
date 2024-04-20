# Summary of "What is DNS?" by Cloudflare

### Overview
The Domain Name System (DNS) functions like the internet's phone book, converting human-friendly domain names into IP addresses that computers use to identify each other. DNS is essential for humans to access websites using domain names instead of numerical IP addresses.

### How DNS Works
DNS resolution involves multiple servers:
1. **DNS Recursor:** Acts like a librarian fetching the requested information.
2. **Root Nameserver:** Directs the recursor to more specific servers.
3. **TLD Nameserver:** Holds information about the domain's last portion (.com, .org, etc.).
4. **Authoritative Nameserver:** Provides the specific IP address of the domain.

### Types of DNS Queries
- **Recursive Query:** The resolver must respond with the requested record or an error.
- **Iterative Query:** The resolver directs the query closer to the detailed information but does not resolve it.
- **Non-recursive Query:** Occurs when the resolver already knows the answer or quickly finds it in its cache.

### DNS Caching
This process enhances efficiency by storing DNS query results for a certain period at different levels (browser, operating system, recursive resolver) to speed up future requests to the same addresses.

For more detailed insights, [read the full article on Cloudflare](https://www.cloudflare.com/learning/dns/what-is-dns/).
