# ifconfig
Interface configuration

---

## Description
Ifconfig is used to configure the kernel-resident network interfaces. It is used at boot time to set up interfaces as necessary. After that, it is usually only needed when debugging or when system tuning is needed.

---

## Syntax
```bash
ifconfig -AaC interface address_family address dest_address parameters
```

---

## Options/Flags
- ###  View network settings of an Ethernet adapter
    ```bash
    $ ifconfig eth0
    ```
- ### Display details of all interfaces, including disabled interfaces
    ```bash
    $ ifconfig -a
    ```
- ### Disable eth0 interface
    ```bash
    $ ifconfig eth0 down
    ```
- ### Enable eth0 interface
    ```bash
    $ ifconfig eth0 up
    ```
- ### Assign IP address to eth0 interface
    ```bash
    $ ifconfig eth0 [ip_address]
    ```


---

## Author
- Fred N. van Kempen
- Alan Cox
- Phil Blundell
- Bernd Eckenfels
- Andi Kleen

---
