# cd
change directory

---

## Description
It is used to change current working directory.
We move in a sub directory or super directory in our system.

---

## Syntax
```bash
cd [directory]
```
---

## Options/Flags
- ###  Move to previous directory.
    ```bash
    $ cd -
    ```
- ### Move to parent directory.
    ```bash
    $ cd ..
    ```
- ### Move to system's working directory.
    ```bash
    $ cd /
    ```
- ### Move to default working directory.
    ```bash
    $ cd
    ```
- ### Move to other user's home directory.
    ```bash
    $ cd ~[username]
    ```
- ### Move to directory with space in it's name.
    ```bash
    $ cd directory\ with\ a\ space\ in\ its\ name
    ```

---

## Exit Status
- **0** = OK
- **>0** = Error
---

## Author
- Ravi Jha

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
