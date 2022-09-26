# ls
list storage

---

## Description
List information about the FILE(s) of the current directory.
It sorts the files alphabetically if tags are not specified.

---

## Syntax
```bash
ls [OPTIONS/FlAGS] [FILE]
```
---

## Options/Flags
- ###  List files one per line.
    ```bash
    $ ls -1
    ```
- ### List all files, including hidden files.
    ```bash
    $ ls -a
    ```
- ### List all files in long listing format.
    ```bash
    $ ls -l
    ```
- ### List all files with trailing directory names and indicating what type files are by putting a slash after directories and a star after executable files
    ```bash
    $ ls -F
    ```
- ### List all files with long format, permissions, ownership, size and modification date of all files. 
    ```bash
    $ ls - la
    ```
- ### Long formated list sorted by size in descending order.
    ```bash
    $ ls -lS
    ```
- ### Long formated list sorted by modification date, oldest being first of all files.
    ```bash
    $ ls - ltr
    ```
- ### List files with size displayed using human-readable units such as KiB, MiB, GiB.
    ```bash
    $ ls -h
    ```
- ### List directories only.
    ```bash
    $ ls -d */
    ```

- ### List file entries by column.
    ```bash
    $ ls -C
    ```
- ### List files with their respective index number.
    ```bash
    $ ls -i
    ```
    `OR`
    ```bash
    $ ls --inode
    ```
- ### List files by sorting with respect to time, newest first.
    ```bash
    $ ls -t
    ```

---

## Exit Status
- **0** = OK
- **1** = Minor problem --> can't access a directory/file.
- **2** = Major problem --> can't access command line arguments.
---

## Author
- Richard M. Stallman
- David MacKenzie.

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
