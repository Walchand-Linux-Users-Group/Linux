# Command
netcat

---

## Description
The Netcat (nc) command is a command-line utility for reading and writing data between two computer networks. The communication happens using either TCP or UDP.

---

## Syntax
```bash
nc [<options>] <host> <port>
```

---

## Options/Flags
- ###  -u = Use UDP connection.
    ```bash
    $ nc -u
    ```
- ### -l = Listen mode (default is client mode).
    ```bash
    $ nc -l
    ```
- ### -e = Program to execute after a connection has been established.
    ```bash
    $ nc -e
    ```


## Author
- Giovanni Giacobbi

---
