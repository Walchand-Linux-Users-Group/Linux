# command

whois

---

## Description

- Identifies a user by user ID or alias.
- `whois` performs the registration record for the domain name or IP address that you specify.
- `whois` is a command-line utility used in Linux systems to retrieve information about domain names, IP addresses, and network devices registered with the Internet Corporation for Assigned Names and Numbers (ICANN).

---

## Syntax

```bash
$ whois [options] [domain_name]
```

---

## Options/Flags

- ### Basic Usage:

  This command retrieves the WHOIS information for the domain _example.com_.

  ```bash
  $ whois example.com
  ```

- ### -h

  Here, `-h` specifies the WHOIS server to use (_whois.example.com_) for querying information about _example.com_.

  ```bash
  $ whois -h whois.example.com example.com
  ```

- ### Querying for IP Addresses:

  Retrieves information about the IP address 8.8.8.8.

  ```bash
  $ whois 8.8.8.8
  ```

- ### -v

  `-v` provides more verbose or detailed output for the domain _example.com_.

  ```bash
  $ whois -v example.com
  ```

- ### -T

  Using `-T` domain specifies that the query is for domain-related information about _example.com_.

  ```bash
  $ whois -T domain example.com
  ```

- ### -i

  `-i` performs a case-insensitive search for _example.com_.

  ```bash
  $ whois -i example.com
  ```

- ### -a
  `-a` returns raw output without filtering or formatting for _example.com_.
  ```bash
  $ whois -a example.com
  ```
- ### Checking Autonomous System Number (ASN):

  This command retrieves information about the Autonomous System Number (ASN) 32934 (Google's ASN) from a specific WHOIS server (whois.radb.net)

  ```bash
  $ whois -h whois.radb.net -- '-i origin AS32934'

  ```

---

## Exit Status

- **0:** The `whois` command completed successfully and retrieved the requested information from the WHOIS database.
- **1:** This status code might indicate a failure or error. It could signify issues like an invalid domain name, network connectivity problems, or other failures during the lookup process.
- **2:** Less commonly used, but it might denote syntax errors in the command itself or specific issues related to the execution of the whois command.

---

## Author

- Elizabeth Feinler

---

## Copyright

GNU General Public License (GPL)<br>
BSD License

---
