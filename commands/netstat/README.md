# netstat

Network statistics

---

## Description
- Netstat command displays various network related information such as network connections, routing tables, interface statistics, etc.

---

## Syntax
```bash
    $ netstat
```

---

## Options/Flags
- ###  -a
    Represents every socket, both non-listening and listening, and every protocol, like UDP, TCP, etc.
    ```bash
    $ netstat -a
    ```
- ### -at
    Represents TCP connections only.
    ```bash
    $ netstat -at
    ```
- ### -au
    Represents UDP connections only.
    ```bash
    $ netstat -au
    ```
- ### -al
    Displays listening sockets only.
    ```bash
    $ netstat -al
    ```
- ### -lt
    Lists only the listening TCP ports.
    ```bash
    $ netstat -lt
    ```
- ### -lu
    Lists only the listening UDP ports.
    ```bash
    $ netstat -lu
    ```
- ### -lx
    Lists only the listening Unix ports.
    ```bash
    $ netstat -lx
    ```
- ### -s
    To list the statistics for all ports.
    ```bash
    $ netstat -s
    ```
- ### -pt
    To display the PID and program names.
    ```bash
    $ netstat -pt
    ```
- ### -c
    To print the netstat information continuously.
    ```bash
    $ netstat -c
    ```
- ### --verbose 
    To get the non-supportive address families in the system.
    ```bash
    $ netstat --verbose
    ```
- ### -r
    To get the kernel routing information.
    ```bash
    $ netstat -r
    ```
- ### -ap | grep ssh
    To get the port on which a program is running.
    ```bash
    $ netstat -ap | grep ssh
    ```
- ### -an | grep ':port number'
    To get the process which is using the given port.
    ```bash
    $ netstat -an | grep ':port number'
    ```

---

## Author
-  Michael Kerrisk

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later. <br/>
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.