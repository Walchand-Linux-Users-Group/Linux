# nslookup

Nslookup stands for "Name Server Lookup" 

---


## Description
It is a useful command for getting information from the DNS server. It is a network administration tool for querying the Domain Name System (DNS) to obtain domain name or IP address mapping or any other specific DNS record. It is also used to troubleshoot DNS-related problems. 
---

## Syntax

```bash
nslookup [option] [domain-name]
```   

---


## Options/Flags
- ###  -type=ns
     Name Server (NS) records store names of the domain's name servers. To see a domain's NS records, type:

    ```bash
    $ nslookup -type=ns [domain-name]
    ```

- ###  -type=mx
     MX records store all relevant Mail Exchange server data. This information is used to route all email requests for the domain to the appropriate mail server.
    ```bash
    $ nslookup -type=mx [domain-name]
    ```
- ###  Reverse DNS Lookup
     While nslookup provides information about a domain name, it can also be used to look for the domain name associated with an IP address.<br>Perform a reverse DNS lookup using the following syntax:
    ```bash
    $ nslookup [ip-address]
    ```

- ###  -type=soa
     Start of Authority (SOA) records provide authoritative information about the domain and the server, such as the email address of the administrator, serial number, refresh interval, query expiration time, etc.<br>View a domain's SOA records by typing:
    ```bash
    $ nslookup -type=soa [domain-name]
    ```

- ### -type=txt
     TXT records contain important information for users outside of the domain. For example, Google and Facebook use TXT records to verify domain ownership <br>View a domain's TXT information by running the following nslookup command: 
     ```bash
    $ nslookup -type=txt [domain-name]
    ```
- ### -type=any
     View all available DNS records of a domain using the any option  
     ```bash
    $ nslookup -type=any [domain-name]
    ```
    
- ### -type=ptr
     Pointer records are used for reverse DNS lookups to confirm that the IP address belongs to a specific domain name. When using the ptr option, type the IP address in reverse, i.e., 1.2.3.4 becomes 4.3.2.1:  
     ```bash
    $ nslookup -type=ptr [reverse-ip-address].in-addr.arpa
    ```
- ### -port=[port-number]
     DNS servers use port 53 to communicate. If you want to check a different port, specify it with the port option: 
     ```bash
    $ nslookup -port=[port-number] [domain-name]
    ```
- ### -debug
     To view information useful for debugging, use the debug option:
     ```bash
    $ nslookup -debug [domain-name]
    ```
---


## Exit Status

- **0**: The query was successful, and the information was retrieved as requested.

- **1**: Typically signifies a general failure or an error in the query. This can cover a range of issues such as an invalid domain name, network connectivity problems, or other failures during the query process.

- **2**: Less commonly used, but in some cases, it might denote syntax errors in the command itself or specific issues related to the execution of the nslookup command.


---


## Author
- Internet Systems Consortium
- Andrew Cherenson
- IBM
- Microsoft
- Lucas Suggs
---


## Copyright
Microsoft Windows
IBM OS/2: Proprietary commercial software
ReactOS: GNU General Public License
