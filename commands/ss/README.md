# ss
Socket Statistics

---

## Description
Another utility to investigate sockets.
It is a potent tool for inspecting and displaying detailed information about network sockets on a Linux system.

---

## Syntax
```bash
ss [options]
```

---

## Options/Flags
- ### Display all sockets.
    ```bash
    $ ss -a
    ```
- ### Show internal TCP information.
    ```bash
    $ ss -i
    ```
- ### Show process using socket.
    ```bash
    $ ss -p
    ```
- ### Print each socket's data on a single line.
    ```bash
    $ ss -O
    ```
- ### Print Sockets TCP / UDP. 
    ```bash
    $ ss -t
    ```
    ```bash
    $ ss -u
    ```
- ### Print socket memory usage. 
    ```bash
    $ ss -m
    ```
- ### Attempts to forcibly close sockets. 
    ```bash
    $ ss -K
    ```
- ### Continually display sockets as they are destroyed.
    ```bash
    $ ss -E
    ```

---

## Author
- Alexey Kuznetsov

---