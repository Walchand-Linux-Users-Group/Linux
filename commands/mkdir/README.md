# mkdir
mkdir - make directories

---

## Description
Create the DIRECTORY(ies), if they do not already exist.
       Mandatory arguments to long options are mandatory for short options too.

---

## Syntax
```bash
mkdir [OPTION]... DIRECTORY...
```
---

## Options/Flags
- ###  set file mode (as in chmod), not a=rwx - umask
    ```bash
    $ mkdir -m, --mode=MODE
    ```
- ### no error if existing, make parent directories as needed
    ```bash
    $ mkdir -p, --parents
    ```
- ### print a message for each created directory
    ```bash
    $ mkdir -v, --verbose
    ```
- ### set SELinux security context of each created directory to the default type
    ```bash
    $ mkdir -Z
    ```
- ### like -Z, or if CTX is specified then set the SELinux or SMACK security context to CTX
    ```bash
    $ mkdir --context[=CTX]
    ```
- ### output version information and exit
    ```bash
    $ mkdir --version
    ```

---

## Reporting Bugs
GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>

---

## Author

- David MacKenzie

---

## Copyright
Copyright © 2020 Free Software Foundation, Inc.  License GPLv3+: GNU GPL version 3 or
       later <https://gnu.org/licenses/gpl.html>.
       This  is free software: you are free to change and redistribute it.  There is NO WAR‐
       RANTY, to the extent permitted by law.
