# cat
Concatenate

---

## Description
It is used to print the content of a file onto the standard output stream.
It is also allows us to write some texts into a file

---

## Syntax
- ### Show the contents of a file
```bash
cat [Filename]
```
- ### Create and edit the file
```bash
cat > [Filename]
```
- ### Append Text to Existing File
```bash
cat >> [Filename]
```
---

## Options/Flags
- ### Display Contents of Multiple Files.
    ```bash
    $ cat [file1] [file2]
    ```
- ### Redirect Contents of a Single File.
    ```bash
    $ cat [file1] > [file2]
    ```
- ### Redirect Contents of Multiple Files.
    ```bash
    $ cat [file1] [file2] > [file3]
    ```
- ### Display the Contents in Reverse Order.
    ```bash
    $ tac [file]
    ```
- ### Append File Contents to Another File.
    ```bash
    $ cat [file1] >> [file2]
    ```
- ### More and Less Options (Manage Large Files).
    ```bash
    $ cat [file] | more
    $ cat [file] | less
    ```
- ### Show Line Numbering.
    ```bash
    $ cat –n [file]
    ```
- ### Show the End of Line.
    ```bash
    $ cat -e [file]
    ```
- ### Show TAB Separated Lines.
    ```bash
    $ cat -t [file]
    ```
- ### Remove Blank Lines
    ```bash
    $ cat -s [file]
    ```
- ###  List All CAT Commands
    ```bash
    $ cat ––help
    ```
---

## Author
- Swarada Bhosale

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
