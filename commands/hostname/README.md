# HOSTNAME
    hostname - show or set the system's host name
    domainname - show or set the system's NIS/YP domain name
    ypdomainname - show or set the system's NIS/YP domain name
    nisdomainname - show or set the system's NIS/YP domain name
    dnsdomainname - show the system's DNS domain name

---

## Description
    Hostname is used to display the system's DNS name

---

## Syntax
```bash
syntax of command
```

---

## Options/Flags
- ###  -a, --alias
    Display the alias name of the host (if used). This option is deprecated and should not be used anymore.
    ```bash
    $ hostname -a
    ```
- ### -A, --all-fqdns
    Displays  all  FQDNs  of the machine. This option enumerates all configured network addresses on all configured network interfaces, and translates them to DNS domain names. Addresses that cannot be translated (i.e. because they do not  have  an  appropriate  reverse  IP  entry)  are
    skipped.  
    Note  that different addresses may resolve to the same name, therefore the output may contain duplicate entries. Do not make any as‐
    sumptions about the order of the output.
    ```bash
    $ hostname -A
    ```
- ### -b, --boot
    Always set a hostname; this allows the file specified by -F to be non-existent or empty, in which case the default hostname localhost will  be used if none is yet set.
    ```bash
    $ hostname -b  
    ```
- ### -d, --domain
    Display  the name of the DNS domain.  Don't use the command domainname to get the DNS domain name because it will show the NIS domain name and not the DNS domain name. Use dnsdomainname instead. See the warnings in section THE FQDN above, and avoid using this option.
    ```bash
    $ hostname -d
    or
    $ hostname -domain
    ```
- ### f, --fqdn, --long
    Display the FQDN (Fully Qualified Domain Name). A FQDN consists of a short host name and the DNS domain name. Unless you are using bind or NIS for  host lookups you can change the FQDN and the DNS domain name (which is part of the FQDN) in the /etc/hosts file. See the warnings in section THE FQDN above und use hostname --all-fqdns instead wherever possible.
    ```bash
    $hostname -f
    ```
- ### -i, --ip-address
    As name suggest it shows the ip address of the machine.
    ```bash
    $ hostname -i
    or
    $ hostname --ip-address
    ```
- ### -I, --all-ip-addresse
    Display  all  network addresses of the host. This option enumerates all configured addresses on all network interfaces. The loopback interface and IPv6 link-local addresses are omitted. Contrary to option -i, this option does not depend on name resolution. Do not make any  assumptions
    about the order of the output
    ```bash
    $ hostname -I
    or
    $ hostname --all-ip-address
    ```
    
---
## AUTHORS
       Peter Tobias, <tobias@et-inf.fho-emden.de>
       Bernd Eckenfels, <net-tools@lina.inka.de> (NIS and manpage).
       Michael Meskes, <meskes@debian.org>