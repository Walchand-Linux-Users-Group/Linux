# command

traceroute

---

## Description

- `traceroute` command in Linux prints the route that a packet takes to reach the host.
- This command is useful when you want to know about the route and about all the hops that a packet takes.
- Below image depicts how traceroute command is used to reach the Google(172.217.26.206) host from the local machine and it also prints detail about all the hops that it visits in between.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/traceroute.png" alt="gfg traceroute">
 
---

## Syntax

```bash
$ traceroute [options]  host_Address [pathlength]
```

---

## Options/Flags

- ### -4

  Use ip version 4 i.e. use IPv4.

  ```bash
  $ traceroute -4 google.com
  ```

- ### -6

  Use ip version 6 i.e. use IPv6.

  ```bash
  $ traceroute -6 google.com
  ```

- ### -F

  Do not fragment packet.

  ```bash
  $ traceroute -F google.com
  ```

- ### -f

  Start from the first_ttl(time to live) hop (instead from 1).

  ```bash
  $ traceroute -f 10 google.com
  ```

- ### -g
  Route the packet through gate.
  ```bash
  $ traceroute -g 192.168.43.45 google.com
  ```
- ### -m
  Set the max number of hops for the packet to reach the destination.Default value is **30**.
  ```bash
  $ traceroute -m 5 google.com
  ```
- ### -n
  Do not resolve IP addresses to their domain names.
  ```bash
  $ traceroute -n google.com
  ```
- ### -p
  Set the destination port to use. Default is **33434**.
  ```bash
  $ traceroute  -p 20292 google.com
  ```
- ### -q
  Set the number of probes per each hop. Default is **3**.
  ```bash
  $ traceroute -q 1 google.com
  ```
- ### packetlen
  The full packet length. Default len is **60 byte** packets.
  ```bash
  $ traceroute  google.com 100
  ```
- ### --help
  Display help messages and exit.
  ```bash
  $ traceroute --help
  ```

---

## Exit Status

- **0:** The traceroute command completed successfully without any errors. It found the route to the destination and finished tracing it.
- **1:** This status code might indicate a generic error. It could signify issues such as improper usage of the command or problems encountered during the traceroute process, like unreachable destinations or network problems.
- **2:** Often used to indicate that the traceroute command encountered syntax errors or invalid command-line options.

---

## Author

- Van Jacobson

---

## Copyright

- BSD License
- GNU General Public License (GPL).

---
