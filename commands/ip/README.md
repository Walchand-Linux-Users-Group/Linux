# ip
Internet Protocol

---

## Description
perform several tasks like assigning an address to a network interface or configuring network interface parameters.

---

## Syntax
```bash
$ ip [ OPTIONS ] OBJECT { COMMAND | help }
```
---

## Options/Flags
- ###  show all IP addresses associated on all network devices.
    ```bash
    $ ip address
    ```
- ###  Show information of particular interface.
    ```bash
    $ ip address show (interface)
    ```
- ###  display link layer information
    ```bash
    $ ip link
    ```
- ### show the statistics of the various network interfaces.
    ```bash
    $ ip -s link
    ```
- ###  helps you to see the route packets your network will take as set in your routing table.
    ```bash
    $ ip route
    ```
- ### assign an IP address to an interface.
    ```bash
    $ ip a add (ip_address) dev interface
    ```
- ###  delete an assigned IP address to an interface.
    ```bash
    $ ip a del (ip_address) dev interface
    ```
- ### enable a network interface.
    ```bash
    $ ip link set (interface) up
    ```
- ### disable a network interface
    ```bash
    $ ip link set (interface) down
    ```

- ###  monitor and displays the state of devices, addresses and routes continuously.
    ```bash
    $ ip monitor
    ```

---

## Exit Status
- **0** = OK
- **1** = Syntax error
- **2** = Kernel error
---

## Author
- Alexey N. Kuznetsov


---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
