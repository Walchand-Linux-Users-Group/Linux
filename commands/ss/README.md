# Command

ss

---

## Description

- Socket Statistics.
- Another utility to investigate sockets.
- It is a potent tool for inspecting and displaying detailed information about network sockets on a Linux system.

---

## Syntax

```bash
$ ss [options]
```

---

## Options/Flags

- ### -a
  Display all sockets.
  ```bash
  $ ss -a
  ```
- ### -i
  Show internal TCP information.
  ```bash
  $ ss -i
  ```
- ### -p
  Show process using socket.
  ```bash
  $ ss -p
  ```
- ### -O
  Print each socket's data on a single line.
  ```bash
  $ ss -O
  ```
- ### -t
  Print Sockets TCP.
  ```bash
  $ ss -t
  ```
- ### -u
  Print Sockets UDP.
  ```bash
  $ ss -u
  ```
- ### -m
  Print socket memory usage.
  ```bash
  $ ss -m
  ```
- ### -K
  Attempts to forcibly close sockets.
  ```bash
  $ ss -K
  ```
- ### -E
  Continually display sockets as they are destroyed.
  ```bash
  $ ss -E
  ```

---

## Author

- Alexey Kuznetsov

---

## Copyright

Copyright © Alexey Kuznetsov. License GPLv3+: GNU GPL version 3 or later.<br>
This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.
