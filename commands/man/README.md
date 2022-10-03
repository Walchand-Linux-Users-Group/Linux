# man

---
###### manual 
## Description
man command in Linux is used to display the user manual of any command that we can run on the terminal.

##### It provides a detailed view of the command which includes 
1. NAME
2. SYNOPSIS
3. DESCRIPTION
4. OPTIONS
5. EXIT STATUS
6. RETURN VALUES
7. ERRORS, FILES
8. VERSIONS, EXAMPLES
9. AUTHORS and SEE ALSO.

---

## Syntax
```bash
$man [OPTION]... [COMMAND NAME]...
```
---

## Options/Flags
- ###  No Option.
It displays the whole manual of the command.
    ```
    $ man [COMMAND NAME]
    ```
- ###  Section-num.
Since a manual is divided into multiple sections so this option is used to display only a specific section of a manual.
    ```
    $ man [SECTION-NUM] [COMMAND NAME]
    ```
    Example:
    ```
    $ man 2 intro
    ```
- ###   -f option.
One may not be able to remember the sections in which a command is present. So this option gives the section in which the given command is present.
    ```
    $ man -f [COMMAND NAME]
    ```
    Example:
    ```
    $ man -f ls
    ```
- ###   -a option.
This option helps us to display all the available intro manual pages in succession.
    ```
    $ man -a [COMMAND NAME]
    ```
    Example:
    ```
    $ man -a intro
    ```
- ###   -k option.
This option searches the given command as a regular expression in all the manuals and it returns the manual pages with the section number in which it is found
    ```
    $ man -k [COMMAND NAME]
    ```
    Example:
    ```
    $ man -k cd
    ```
- ###   -w option.
This option returns the location in which the manual page of a given command is present.
    ```
   $ man -w [COMMAND NAME]
    ```
    Example:
    ```
    $ man -w ls
    ```
- ###   -I option.
It considers the command as case sensitive.
    ```
   $ man -I [COMMAND NAME]
    ```
    Example:
    ```
    $ man -I printf
    ```


---



## Author
- Rohit Soni
- eference :- [WEBSITE](https://www.geeksforgeeks.org/man-command-in-linux-with-examples/#:~:text=man%20command%20in%20Linux%20is,EXAMPLES%2C%20AUTHORS%20and%20SEE%20ALSO.)

---

## Copyright
Copyright © 2022 Free Software Foundation, Inc. License GPLv3+: GNU GPL version 3 or later.
This is free software, you are free to change and redistribute the information. There is NO WARRANTY, to the extent permitted by law.
