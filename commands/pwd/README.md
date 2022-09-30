# pwd
pwd - print name of current/working directory

---

## Description
Print the full filename of the current working directory.

---

## Syntax
```bash
pwd [OPTION]
```
---

## Options/Flags
- ###  use PWD from environment, even if it contains symlinks
    ```bash
    $ pwd -L
    ```
    `OR`

    ```bash
    $ pwd --logical
    ```
- ###  avoid all symlinks
    ```bash
    $ pwd -P
    ```
    `OR`

    ```bash
    $ pwd --physical
    ```
- ### Display this help and exit
    ```bash
    $ pwd -h
    ```
    `OR`

    ```bash
    $ pwd -h
    ```
- ### Output version information and exit
    ```bash
    $ pwd --version
    ```
- ### If no option is specified, -P is assumed. ###
  
---

## REPORTING BUGS  
- GNU coreutils online help:
       <https://www.gnu.org/software/coreutils/>
- Report any translation bugs to
       <https://translationproject.org/team/>

---

## Author
- Jim Meyering

---

## Copyright
Copyright © 2020 Free Software Foundation, Inc.  License GPLv3+:
GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute
it.  There is NO WARRANTY, to the extent permitted by law.