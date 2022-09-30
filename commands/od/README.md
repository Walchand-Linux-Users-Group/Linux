# od
display octal form

---

## Description
It is used to display files in different formats.
We can represent files in octal, hexadecimal, string format with or without offset.

---

## Syntax
```bash
od [FILE]
```
---

## Options/Flags
- ###  Display file in verbose mode (i.e without replacing duplicate lines with *)
    ```bash
    $ od -v [FILE]
    ```
- ### Display in Hexadecimal Format
    ```bash
    $ od -x [FILE]
    ```
- ### Display in Octal Format
    ```bash
    $ od -b [FILE] OR od [FILE]
    ```
- ### Display in String Format
    ```bash
    $ od -c [FILE]
    ```
- ### Display in String Format without offset
    ```bash
    $ od -An -c [FILE]
    ```
- ### Display as Octal 2 Byte Units
    ```bash
    $ od -o [FILE]
    ```

---

## Exit Status
- **0** = OK
- **>0** = Error
---

## Author
- Jim Meyering

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
