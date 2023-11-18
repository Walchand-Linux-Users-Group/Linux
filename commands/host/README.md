# host

Host command in Linux system is used for DNS (Domain Name System) lookup operations

---


## Description
 This command is used to find the IP address of a particular domain name or if you want to find out the domain name of a particular IP address the host command becomes handy. You can also find more specific details of a domain by specifying the corresponding option along with the domain name.
---

## Syntax

```bash
host [-aCdlriTWV] [-c class] [-N ndots] [-t type] [-W time] [-R number] [-m flag] hostname [server]
```   

---

## Note
**host command without any option:** It will print the general syntax of the command along with the various options that can be used with the host command as well as gives a brief description about each option.

## Options/Flags
- ###  host domain_name:
    This will print the IP address details of the specified domain.

    ```bash
    $ host wcewlug.org
    ```

- ###  host IP_Address:
   This will display the domain details of the specified IP Address.
    ```bash
    $ host 52.25.109.230
    ```
- ###  -a or -v
     It used to specify the query type or enables the verbose output.
    ```bash
    $ host -a wcewlug.org 
    ```

- ###  -t
    It is used to specify the type of query
    ```bash
    $ host -t ns wcewlug.org 
    ```

    To print SOA record
    ```bash
    $ host -t SOA wcewlug.org  
    ```
     
    To print txt record
    ```bash
    $ host -t txt wcewlug.org  
    ```

- ### -C
     In order to compare the SOA records on authoritative nameservers.
     ```bash
    $ host -C wcewlug.org 
    ```
- ### -R
     In order to specify the number of retries you can do in case one try fails. If anyone try succeeds then the command stops.
     ```bash
    $ host -R 3 wcewlug.org 
    ```

- ### -l
     In order to list all hosts in a domain.For this command to work you need to be either an admin or a node server.
     ```bash
    $ host -l wcewlug.org 
    ```

---


## Exit Status

- **0**: The host command completed successfully and obtained the requested information, such as resolving a domain name to an IP address.

- **1**: This status code might indicate a failure or error. It could signify issues like an invalid domain name, network connectivity problems, or other failures during the lookup process.

- **2**: Less commonly used, but it might denote syntax errors in the command itself or specific issues related to the execution of the host command.


---


## Author
- Internet Systems Consortium (ISC)
---


## Copyright
Mozilla Public License 2.0
